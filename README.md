# Digital Nurture 5.0 — Deep Skilling (Java FSE React)

My solutions to the **mandatory hands-on exercises** for the Cognizant DN 5.0 Deep Skilling
program (Java FSE React track). Exercises are organized **week-wise** as required by the handbook.

> Source exercise statements: [Cognizant public repo](https://github.com/seshadrimr/Digital-Nurture-JavaFSE/tree/main/Java%20FSE/Deepskilling)

## Progress

| Week | Skill | Mandatory hands-on | Status |
|------|-------|--------------------|--------|
| 1 | Design Patterns & Principles | Ex1 Singleton, Ex2 Factory Method | ✅ |
| 1 | Data Structures & Algorithms | Ex2 E-commerce Search, Ex7 Financial Forecasting | ✅ |
| 1 | PL/SQL Programming | Ex1 Control Structures, Ex3 Stored Procedures | ✅ |
| 1 | TDD — JUnit 5 | Ex1 Setup, Ex3 Assertions, Ex4 AAA/Fixtures | ✅ |
| 1 | TDD — Mockito | Ex1 Mocking & Stubbing, Ex2 Verifying Interactions | ✅ |
| 1 | Logging — SLF4J | Ex1 Error messages & warning levels | ✅ |
| 2 | Spring Core & Maven | Ex1 Basic App, Ex2 Dependency Injection, Ex4 Maven Project | ✅ |
| 2 | Spring Data JPA + Hibernate | Quick Example, Add Country, Query Methods, O/R Mapping, HQL & Native Query | ✅ |
| 3 | Spring REST using Spring Boot 3 | Web Project, Load Country from XML, Hello World, Country service, Get by code, JWT auth | ✅ |

## Layout

```
Week1/
  01-DesignPatterns/       plain Java  (Singleton, Factory Method)
  02-DataStructures/       plain Java  (Search, Recursion)
  03-PLSQL/                Oracle PL/SQL scripts
  04-Testing-JUnit-Mockito-SLF4J/   Maven project (tests + logging)
Week2/
  01-SpringCoreMaven-LibraryManagement/   Maven + Spring XML config
  02-SpringDataJPA-orm-learn/             Spring Boot + H2 in-memory DB
Week3/
  01-SpringREST-spring-learn/             Spring Boot 3 REST + Spring Security JWT
```

Each folder has its own `README.md` explaining the exercise, how to run it, and the expected output.

## How to run (quick reference)

- **Plain Java** (Design Patterns, DSA): `javac *.java && java Main` inside the exercise folder.
- **PL/SQL**: run the `.sql` scripts in Oracle SQL Developer / any Oracle instance (run schema setup first).
- **Maven projects** (Week1/04, Week2/01): `mvn test` or `mvn exec:java`.
- **Spring Boot** (Week2/02): `mvn spring-boot:run` — uses H2, no database install needed.

See [SUBMISSION.md](SUBMISSION.md) for how this repo was created and shared.
