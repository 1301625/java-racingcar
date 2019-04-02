# 2주차 미션 - 자동차 경주 게임
 > 우아한테크코스::프리코스

# 진행 방식
- 매주 진행할 미션은 금요일에 메일로 전송되고, 미션 제시 다음 주 목요일까지 구현을 완료해 제출해야 한다.
- 매주 미션은 기능 요구사항, 프로그래밍 요구사항, 과제 진행 요구사항 세 가지로 구성되어 있다
  - 세 개의 요구사항을 만족하기 위해 노력한다. 특히 기능을 구현하기 전에 
  - 기능 목록을 만들고, 기능 단위로 commit 하는 방식으로 진행한다.

# 문제설명
  
- 기능 요구사항
  - 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.
  - 각 자동차에 이름을 부여할 수 있다. 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력한다.  
  - 자동차 이름은 쉼표(,)를 기준으로 구분하며 이름은 5자 이하만 가능하다.
  - 사용자는 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.
  - 전진하는 조건은 0에서 9 사이에서 random 값을 구한 후 random 값이 4 이상일 경우 전진하고, 3 이하의 값이면 멈춘다.
  - 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다. 우승자는 한 명 이상일 수 있다.




# 기능 구현
- Input 클래스 생성
  - 자동차 입력 및 저장 enter_Car_Name()
  - 자동차 이름 검사 및 재 입력
  - Car 객체 생성 및 자동차 이름 초기화

- Forward_Util 클래스 
  - 자동차 객체 출력
  - 사용자 횟수 입력
  - 랜덤 숫자 생성
  - 전진 조건 생성 및 포지션 값 증가
  - 포지션 값 dash 출력
  - 우승자 출력

- Process 클래스
    - 게임 진행 메소드