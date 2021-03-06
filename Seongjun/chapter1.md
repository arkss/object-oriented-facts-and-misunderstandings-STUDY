# 협력하는 객체들의 공동체

> 시너지를 생각하라. 전체는 부분의 합보다 크다.

* 객체지향이란 실세계를 직접적이고 직관적으로 모델링할 수 있는 패러다임
* 객체지향 프로그래밍이란 현실 속에 존재하는 사물을 최대한 유사하게 모방해 소프트웨어 내부로 옮겨오는 작업
* 그 결과물, 객체지향 소프트웨어는 실세계의 투영
* 객체란 현실 세계에 존재하는 사물에대한 추상화

* **But** 애플리케이션을 개발하면서 객체에 직접적으로 대응되는 실세계의 사물을 발견할 확률은 높지 않음
* 있더라도 객체와 사물 간의 개념적 거리는 멀다.
  * 마치 건물의 방화벽과 소프트웨어 방화벽 사이의 의미적 거리만큼... 연관성이..
* 객체지향의 목표는 실세계를 모방하는 것이 아닌 새로운 세계를 창조하는 것

## 협력하는 사람들

* 손님, 캐시어, 바리스타 사이의 **협력**
* 커피를 주문하는 손님, 주문을 받는 캐시어, 커피를 제조하는 바리스타라는 **역할**
* 자신이 맡은 바 **책임**

### 요청과 응답으로 구성된 협력

* 요청은 연쇄적으로 발생한다.
* 요청에 응답함
* 응답도 연쇄적으로 전달

### 역할과 책임

* 역할은  의미적으로 책임을 내포
* 여러 사람이 동일한 역할을 수행할 수 있다.
* 역할은 대체 가능성을 의미한다 - 대체 가능 substitutable
* 책임을 수행하는 방법은 자율적으로 선택할 수 있다. - 동일 요청 서로 다른 방식 응답, 다형성
* 한 사람이 동시에 여러 역할을 수행할 수 있다.

## 역할 책임 협력

### 기능을 구현하기 위해 협력하는 객체들

* 사람 -> 객체 / 요청 -> 메시지 /  처리하는 방법 -> 메서드

### 역할과 책임을 수행하며 협력하는 객체들

* 시스템의 기능은 객체들이 성실히 협력하여 일궈낸 결실
* 애플리케이션의 기능은 더 작은 책임으로 분할되고 책임은 적절한 역할을 수행할 수 있는 객체에 의해 수행된다.

## 협력 속에 사는 객체

* 협력에 참여하는 주체는 객체
* 객체가 존재하지 않으면 의미 없다
* 객체는 충분히 협력적이어야 한다.
  * 혼자 다 처리하는 전지전능한 객체는 복잡도로 망함
  * 명령에따라 수동적으로 행동하는 게 아닌 요청에 응답할 뿐
* 충분히 자율적이여야한다.

### 상태와 행동을 함께 지닌 자율적인 객체

* 상태와 행동을 함께 지닌 실체
* 다른 객체가 가 무엇을 수행하는지는 알 수 있지만 어떻게 숳행하는지는 모름

### 협력과 메시지

* 객체지향에서는 한 가지 의사소통 수단만이 조재 - 메시지
* 송신자, 수신자

### 메서드와 자율성

* 객체가 수신된 메시지를 처리하는 방법을 메서드
* 외부의 요청이 무엇인지 표현하는 메시지와 요청을 처리하기 위한 구체적인 방법인 메서드를 분리하는 게 자율성을 높이는 핵심 메커니즘
* 캡슐화와 연관

## 객체지향의 본질

* 자율적인 객체들의 공동체
* 상태와 행위
* 협력, 역할, 책임
* 메시지, 메서드
* 클래스가 객체지향 프로그래밍 언어의 관점에서 매우 중요한 구성요소지만 핵심을 이루는 중심 개념이라고 하기엔 무리가 있다.
* 프로토타입 기반의 객체지향 언어에서는 상속 역시 클래스가 아닌 객체 간의 위임 메커니즘을 기반으로 함
* 







