# java-racingcar-precourse
- - -
## 구현할 기능 목록

### [레이싱 정보 입력]
 - [ ] 경주할 레이싱 자동차 이름 입력 받기 
   - #### 쉼표(,)를 기준으로 구분
   - #### 이름 5자 이하만 가능 
    ##### [예시]


     경주할 자동차 이름을 입력하세요.(이름은 쉼표(,) 기준으로 구분)
     pobi,woni,jun

  - [ ] 레이싱 횟수 입력 받기
    - #### 정수 입력 
      - #### 시도할 횟수는 몇 회인가요?
    #### [예시]
        5

## [레이싱 진행]
- ####  전진 조건 판단 
  - [ ] 각 자동차마다 0~9 사이의 정수 무작위 값을 선정
  - [ ] 무작위 값이 4 이상이면 전진
  - [ ] 자동차마다 시도 횟수만큼 미리 전진 조건 판단 
  
- #### 레이싱 기록 출력
  - [ ] 레이싱 현황 초기화 
  - [ ] 레이싱 횟수마다 전진 조건 만족 시, 자동차 한 칸(-) 전진
  - [ ] 레이싱 현황 갱신 후, 출력 
    - #### [예시]
            실행 결과
            pobi : -
            woni :
            jun : -
    
            pobi : --
            woni : -
            jun : --

            pobi : ---
            woni : --
            jun : ---
    
            pobi : ----
            woni : ---
            jun : ----
    
            pobi : -----
            woni : ----
            jun : -----


## [레이싱 결과 출력]
- [ ] 우승자 출력
- #### [출력 형식] 
- #### 최종 우승자 : 레이싱 자동차1, 레이싱 자동차2
  - #### [단독 우승자 예시]
        최종 우승자 : pobi

  - #### [공동 우승자 예시]
        최종 우승자 : pobi, jun
        
  
