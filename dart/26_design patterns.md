### 응집도 (Cohesion)
- 모듈이 하나의 목적을 수행하는 요소들간의 연관성 척도
- 모듈 내부의 기능적인 응집 정도를 나타냄
- 높을수록 좋다

### 결합도 (Coupling)
- 모듈이 다른 모듈에 의존하는 정도의 척도
- 모듈과 모듈간의 상호 결합 정도를 나타냄
- 낮을수록 좋다

💡추가적으로 인터페이스에 의존하는 코드 작성은 낮은 결합도를 얻을 수 있다고 한다

### 6가지 코드 작성의 원칙
DRY - 중복 코드가 있다면 메소드로 분리한다
PIE - 명확하고 표현력 있게 기술하자 (컨벤션을 따르자,매직 넘버에 이름을 붙이자)
SRP - 1개의 클래스는 1개의 일만한다.
OCP - 인터페이스를 적극 활용하여 수정 없이 확장 가능하도록 하자.
SDP - 안전한 것(인터페이스에)에 의존하라
ADP - 의존 관계에 사이클이 발생되지 않게 한다

### SOLID 원칙
![image](https://github.com/Gunbam27/TIL/assets/95085649/48ea456c-47c9-4f10-bc88-ee9f2bb27b55)

### GoF의 23가지 디자인 패턴
예로 아래의 내용이있다.

- Factory 패턴 : 인스턴스를 만드는 패턴
- Singleton 패턴 : 1개의 인스턴스만 생성되는 것을 보증하기 위한 패턴
- Decorator 패턴 :  여러번 감싸는 패턴
- Iterator : 반복 구조
- Facade : 내부를 감추고 심플하게 Repository 패턴이 Facade 패턴이다
- Strategy (전략 패턴) : 갈아 끼우기 쉽게
- Observer 패턴 : 옵저버 패턴(observer pattern)은 객체의 상태 변화를 관찰하는 관찰자들, 즉 옵저버들의 목록을 객체에 등록하여 상태 변화가 있을 때마다 메서드 등을 통해 객체가 직접 목록의 각 옵저버에게 통지하도록 하는 디자인 패턴이다.   콜백함수으로 구현되기도 한다.

### 아키텍쳐 디자인 패턴
소프트웨어를 작성함에 있어 코드 뿐만 아니라 전체적인 구조(Architecture)에 대한 좋은 패턴도 존재한다.
- MVC
- MVC2
- MVP
- MVI
- MVVM