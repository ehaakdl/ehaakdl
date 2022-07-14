## Back-end engineer

#### Skill
spring boot, java, jpa, mybatis, elk, redis, gradle, docker

#### My Rule

- 예외를 잘 활용하자(특히 실패원인은 작성한 개발자만 알 수 있다. 그래서 예외 메시지에 자세하게 적어줘야 로그를 보고 쉽게 대응 할 수 있다.)

- enum 같은 상수로 관리하면 일관되게 공통 코드를 관리할 수 있다!

- Map, Object, JsonObject 같이 모호한 Type으로 매개변수나 아웃풋을 내지말자 관리하기 너무 힘들다

- 테스트 코드 작성하자 서비스 로직 수정될 떄 같이 바껴야 한다는 단점이 있지만, 시스템이 보험을 든다 생각하면 나쁘지 않다!

- @RestControllerAdvice 써서 특정 예외에 따른 응답 처리는 기본! 예외 처리 안해주면 exception 그대로 발생하거든!! 스프링 쓴다면 꼭 예외는 의미있게 잘 처리하자! 이건 controller 단 뿐만 아니라 Filter 나 어디서든 필수다!
