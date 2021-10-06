### 상황은 다음과 같다.

Flyer, Challenger, Beginner, Primer 아니 여기에 Disciple 까지 어떻게 분배해야 가장 효과적일까?

### 문제 해결의 가설은 다음과 같다.

- Disciple - Flyer - Challenger - Beginner - Primer 순서대로 영어로 말하는데 자신이 높다.
- 영어로 말하는데 자신 없는 사람끼리 모이면 Casual Talk가 진행되지 않는다.
- 한 조에 4명 정도면 적당하다. (3명은 괜찮지만 5명은 권장되지 않는다.)

### 원하는 문제 해결 결과는 이러하다.

- 각 레벨별 인원의 수를 입력한다.
- 조마다 레벨별 인원 수를 출력한다.
- 출력된 조를 보며 인원을 나눈다.

### 그러면 문제를 해결하는 알고리즘을 작성한다.

1. 총 인원수를 각 조별 인원 수로 나눠서 전체 조의 수를 구한다.
   - 5명인 조를 피하기 위해서, 조의 수는 올림처리한다.
     - 예를 들면 21명이 왔다면, `21/4 = 5.25`지만, 5조를 만들면 5명인 조가 하나가 생기니, 6조로 한다.
     - 이 경우엔, 4, 4, 4, 3, 3, 3으로 나누어지게 된다.
2. 자신감이 높은 순으로 정렬한다.
3. 각 조에 자신감이 높은 순으로 순차적으로 배치한다.

---

### 사용자 Interface는 어떻게 제공해야 하는가?

- 휴대폰을 사용해 접근할 수 있으면 좋다.
- 앱을 만드는 것은 너무 무겁고 필요없다.
- 웹 서비스로 제공하는 것이 좋다.

  - 간단한 HTML 포맷으로 제공할 수 있다.
  - 내장된 js를 통해서 로직을 구성할 수 있다.

- 웹 호스팅은 어떻게 할 것인가? → 깃허브 호스팅으로 처리할 수 있나? `okay`
