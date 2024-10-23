# java-racingcar-precourse

## 구현 기능 목록

1. 자동차를 생성한다.
   - [x] 사용자 입력을 "," 로 구분하여 각각의 이름으로 분리한다.
     - 입력이 null 또는 "" (빈문자열) 일 경우 예외를 던진다.
   - [x] 자동차의 이름이 고유하도록, 중복되는 이름이 있으면 예외를 던진다.
   - [x] 이름이 5자 초과인 경우 생성에 실패한다.


2. 자동차를 움직인다.
   - [x] 자동차가 움직였을 때, 이동 거리를 1 증가시킨다.
   - [x] 무작위 값이 4 이상일 경우만 움직인다.


3. 경기장을 진행시킨다.
   - [ ] 경기 진행 횟수만큼 경기를 진행한다.
   - [ ] 1회 경기 진행 시마다 실행 결과를 출력한다.


4. 경주 게임의 승자를 가른다.
   - [ ] 이동 거리를 통해 우승자를 선별한다.


5. 사용자 입력 검즘 및 우승자를 출력한다.
   - [ ] 시도할 횟수가 양의 정수가 아닌 경우 예외를 던진다.
   - [ ] 우승자를 출력한다.
