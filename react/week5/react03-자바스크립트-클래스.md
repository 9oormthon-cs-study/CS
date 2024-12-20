# 자바스크립트 클래스란 무엇인가요?
자바스크립트 클래스는 ES6에서 도입된 개념으로, 객체지향 프로그래밍을 위해 만들어진 문법적 설탕입니다. 함수 기반으로 클래스를 정의하던 이전 방식과 달리, 클래스를 통해 더 간결하고 직관적인 객체 지향 프로그래밍이 가능해졌습니다. 다만 ES6의 클래스는 사실상 프로토타입을 기반으로 동작하며 클래스를 사용하여 작성된 코드도 내부적으로는 프로토타입을 사용해 상속 구조를 형성합니다.

## static 키워드는 무엇인가요?
static 키워드를 통해 정적 메서드로 정의하여 클래스 인스턴스가 아니라 클래스 자체에 속한 메서드로 호출할 수 있습니다. 즉, 인스턴스를 생성하지 않고 불러낼 수 있어 독립적이며 메모리 절약이 가능하다. 유틸리티 함수로 사용 가능

### 메모리 관점에서 단점은 무엇인가요?
인스턴스가 존재하지 않더라도 메모리에 할당되므로, static 메서드를 많이 정의하면 인스턴스와 관련 없는 메서드까지 메모리에 남아있게 됩니다. 무분별한 static 키워드 사용은 주의해야합니다.

## 자바스크립트의 상속
자바스크립트는 프로토타입을 통해 객체지향을 표방함. 프로토타입 체인을 통해 태초의 데이터 타입으로부터 상속받은 값들을 가지고 있음. 최상위 객체 Object를 상속받음

## Reference
- [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
- [mordern-js](https://ko.javascript.info/class)
- [poiemaweb](https://poiemaweb.com/js-prototype)
