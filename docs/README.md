## 구현 기능 목록

- 1 - 9 사이의 서로 다른 임의의 수 3개 생성한다. ✅
- 사용자로부터 서로 다른 3개의 숫자를 입력 받는다. ✅
- 입력받은 숫자와 생성한 숫자를 비교해 계산한 결과를 출력한다. ✅

  - 결과 계산은 볼, 스트라이크 누적 갯수로 표시한다.
    - 같은 수가 같은 자리에 있다면 '스트라이크' ✅
    - 같은 수가 다른 자리에 있다면 '볼' ✅
    - 같은 수가 전혀 없다면 '낫싱' ✅

- 생성한 숫자를 모두 맞출 때까지 위 과정 반복 ✅
- 게임이 종료되었다면, 사용자는 게임 '다시 시작' 또는 '완전 종료' 중 선택한다. ✅

### 에러 처리
- 사용자의 잘못된 입력에 대해 `IllegalArgumentException` 발생시킨 후 애플리케이션 종료  ✅
