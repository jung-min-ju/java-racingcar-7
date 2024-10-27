# java-racingcar-precourse

# 자동차 경주 게임

## 구현할 기능 목록

### 1. 입력 처리
- [ ] 사용자로부터 자동차 이름과 경주 횟수를 입력받는다.
- [ ] 입력 값의 유효성을 검사하여 잘못된 값이 입력되면 예외를 처리한다.

### 2. 자동차 경주 진행
- [ ] 입력받은 자동차 이름에 따라 자동차 객체를 생성한다.
- [ ] 각 자동차가 무작위로 움직인다. (0~9 사이의 랜덤값이 4 이상일 경우 전진)
- [ ] 경주를 여러 턴에 걸쳐 진행하며, 각 턴마다 모든 자동차의 위치를 업데이트한다.

### 3. 출력 처리
- [ ] 경주 중 각 턴에서 모든 자동차의 현재 상태를 출력한다.
- [ ] 최종 우승자를 출력한다.

### 4. 결과 계산
- [ ] 우승자는 가장 멀리 이동한 자동차로 결정된다.
- [ ] 동일한 거리만큼 이동한 자동차가 여러 대일 경우, 공동 우승자가 된다.

### 5. 테스트
- [ ] 사용자가 빈 값을 입력한 경우
- [ ] 사용자가 정해진 구분자 외의 특수 문자를 입력한 경우
- [ ] 사용자가 중복된 자동차 이름을 입력한 경우
- [ ] 사용자가 자동차 이름을 5글자를 초과해 입력한 경우
- [ ] 사용자가 경기 횟수에 대해 숫자가 아닌 값을 입력한 경우
- [ ] 사용자가 경기 횟수에 대해 음수를 입력한 경우
- [ ] 인자로 유효하지 않은 타입이 들어온 경우