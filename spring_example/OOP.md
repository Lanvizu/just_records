# OOP
Object-Oriented Programming (OOP)는 '객체'라는 개념을 중심으로 사고하는 방식을 요구한다.

프로그램내에서 객체들이 주체성을 가진 존재처럼 행동하는 환경을 만들어낸다.

![image](https://github.com/user-attachments/assets/1bc0c391-a9da-4ea4-a59a-aa7878f2ac69)

## 객체 지향 프로그래밍(OOP)의 4가지 특성

### **캡슐화**
- **정의**: 데이터와 그 데이터를 처리하는 메서드를 하나로 묶는 것.
- **특징**:
  - 객체 내부에 데이터가 존재하며, 외부에서 직접적인 접근 불가 -> *정보 은닉*.
  - 객체 내부의 메서드를 통해서만 데이터 조작 가능.
  - 객체 간의 결합도를 낮추고, 시스템을 더욱 견고하게 만듦.

### **상속**
- **정의**: 이미 존재하는 클래스(부모 클래스)를 바탕으로 새로운 클래스를 생성.
- **특징**:
  - 부모 클래스의 속성과 메서드를 모두 물려받음.
  - 새로운 속성이나 메서드를 추가할 수 있음.
  - 공통된 기능은 부모 클래스에 정의하고, 자식 클래스는 그 기능을 상속받아 사용 -> 코드 중복 방지.

### **다형성**
- **정의**: 동일한 인터페이스를 통해 여러 다른 객체들이 각기 다른 방식으로 동작 가능.
- **특징**:
  - 같은 함수 호출이라도 객체 종류에 따라 메서드가 달라질 수 있음.
  - '늦은 바인딩'을 통해 어떤 메서드를 호출할지 결정.
  - 다양한 객체들을 동일한 방식으로 다룰 수 있어 코드의 유연성과 재사용성을 높여줌.

### **추상화**
- **정의**: 복잡한 시스템을 단순화하여 중요한 부분만 드러내고 불필요한 세부 사항은 감춤.
- **특징**:
  - 외부에서는 해당 객체가 어떤 데이터를 가지고 있는지 알 필요 없음.
  - 객체가 제공하는 메서드를 통해서만 상호작용 가능.
  - 캡슐화를 통해 실현되며, 객체 내부의 복잡성을 숨기고 사용자에게 간결한 인터페이스 제공. 


## 객체에 대한 사고방식의 전환

- **OOP 이해**: 객체에 대한 사고방식 전환 필요.
- **현실 세계의 물체**:
  - 대부분 수동적 존재이며 외부 조작 없이는 변화가 없음.
- **OOP 세계의 객체**:
  - 능동적이고 자기 주관을 가짐.
  - '물체'보다 '객체'라는 용어가 적합.
  - 일부 이론에서는 거의 완벽한 주체성으로 간주.
- **기본 철학**: 현실의 물체보다 더 능동적으로 동작.

![image](https://github.com/user-attachments/assets/f06a164c-7305-4345-8b0f-c2365e972d95)

출처 - https://blog-full-of-desire-v3.vercel.app/post/-oop---oop-/