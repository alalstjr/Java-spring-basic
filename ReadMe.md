--------------------
# Spring Basic 공부 노트
--------------------

# 목차

- [1. Spring 핵심](#Spring-핵심)
- [2. 객체 지향](#객체-지향)
  - [2-1. 객체 지향 프로그래밍](#객체-지향-프로그래밍)
  - [2-2. 스프링과 객체 지향](#스프링과-객체-지향)

# Spring 핵심

1. 스프링은 자바 언어 기반의 프레임워크
2. 자바 언어의 가장 큰 특징으로 `객체 지향 언어`
3. 스프링은 `객체 지향 언어가 가진 강력한 특징을 살려내는 프레임워크`
4. 결론 스프링은 좋은 객체 지향 애플리케이션을 개발할 수 있게 도와주는 프레임워크

# 객체 지향

1. 추상화
2. 캡슐화
3. 상속
4. 다형성

## 객체 지향 프로그래밍

객체 지향 프로그래밍은 컴퓨터 프로그램을 명렁어의 목록으로 보는 시각에서 벗어나 여러개의 독립된 단위,  
즉 `"객체"들의 모임`으로 파악하고자 하는 것이다.   
각각의 `객체는 메시지를 주고받고, 데이터를 처리`할 수 있다.

객체 지향 프로그래밍은 프로그램을 `유연하고 변경이 용이`하게 만들기 때문에 대규모 소프트웨어 개발에 많이 사용된다.

- 역할(인터페이스)과 구현을 분리 
  - 장점
    - 확장 가능한 설계
    - 클라이언트에 영향을 주지 않는 변경 가능
    - 인터페이스를 안정적으로 잘 설계하는 것이 중요
  - 단점
    - 역할(인터페이스) 자체가 변하면, 클라이언트, 서버 모두에 큰 변경이 발생
    
## 스프링과 객체 지향

- 다형성이 가장 중요
- 스프링은 다형성을 극대화해서 이용할 수 있게 도와준다.
- 스프링에서 이야기하는 제어의 역전(IoC), 의존관계 주입(DI)은 다형성을 활용해서 역할과 구현을 편리하게 다룰 수 있도록 지원한다.
- 스프링을 사용하면 마치 레고 블럭 조립하듯이 구현을 편리하게 변경할 수 있다.

## 좋은 객체 지향 설계의 5가지 원칙 (SOLID)