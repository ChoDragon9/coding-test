# BigInt
- BigInt는 Number 원시 값이 안정적으로 나타낼 수 있는 최대치인 2^53 - 1 보다 큰 정수를 표현할 수 있는 내장 객체다.
- BigInt는 정수 리터럴 뒤에 n을 붙이거나 (예: 10n) 함수 `BigInt()`를 호출해 생성할 수 있다.
- BigInt의 typeof 는 `bigint`다.
- BigInt는 제약사항이 있다.
  - Math 객체의 메서드와 함께 사용할 수 없다.
  - Number와 혼합해 사용할 수 없다. 
