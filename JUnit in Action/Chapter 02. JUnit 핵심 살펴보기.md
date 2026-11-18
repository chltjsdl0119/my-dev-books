# Chapter 02. JUnit 핵심 살펴보기

## 2.1 핵심 애너테이션

> - 테스트 클래스: 클래스, 정적 클래스, 하나 이상의 테스트 메서드를 포함하는 @Nested 애너테이션이 붙은 내부 클래스를 말한다.
> - 테스트 메서드: @Test, @RepeatedTest, @ParameterizedTest, @TestFactory, @TestTemplate 애너테이션이 붙은 메서드를 말한다.
> - 생애 주기 메서드:@BeforeAll, @AfterAll, @BeforeEach, @AfterEach 애너테이션이 붙은 메서드를 말한다.

- 테스트는 실행 순서에 관계없이 동일한 결과를 얻을 수 있어야 하는 것이 당연하다.
