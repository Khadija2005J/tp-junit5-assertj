# JUnit 5 & AssertJ – Testing Practice

**A Java exercise on unit testing with JUnit 5 and AssertJ, following the OpenClassrooms Java testing course.**

The code under test is a small `Calculator` class. The test class shows the main JUnit 5 features step by step.

## What is covered

- **Test lifecycle** – `@BeforeAll`, `@BeforeEach`, `@AfterEach`, `@AfterAll` (with total test duration)
- **Arrange / Act / Assert** structure
- **Fluent assertions** with AssertJ (`assertThat(...).isEqualTo(...)`, assertions on sets)
- **Parameterized tests** – `@ParameterizedTest` with `@ValueSource` and `@CsvSource`
- **Timeouts** – `@Timeout` on a slow method
- **Test-driven development** – `digitsSet()` written red → green

## Run the tests

**Prerequisites:** Java 17+, Maven.

```bash
git clone https://github.com/Khadija2005J/tp-junit5-assertj.git
cd tp-junit5-assertj
mvn test
```

## Tech stack

Java 17, Maven, JUnit 5 (Jupiter), AssertJ.

## Author

Khadija Alaoui Mrani – [GitHub](https://github.com/Khadija2005J)
