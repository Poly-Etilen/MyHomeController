# Project Instructions

## Tech Stack

- Java 21
- Spring Boot 4
- PostgreSQL
- JPA
- QueryDSL
- Redis
- RabbitMQ

## Architecture

- Controller
- Service
- Repository

각 계층의 책임을 명확하게 분리한다.

## Coding Rules

- DTO와 Entity를 분리한다.
- Entity를 Controller의 응답으로 직접 반환하지 않는다.
- 비즈니스 로직은 Service 계층에서 처리한다.
- Repository에서는 데이터 접근만 담당한다.
- Optional을 무분별하게 사용하지 않는다.
- 코드는 임의로 절대 수정하지 않는다.
- 반드시 채팅으로 코드를 보여주면 사용자가 직접 작성한다.
- 

## Naming

- 클래스: PascalCase
- 메서드/변수: camelCase
- 상수: UPPER_SNAKE_CASE

## Git

커밋 메시지는 다음 형식을 사용한다.

feat: 기능 추가
fix: 버그 수정
refactor: 리팩토링
docs: 문서 수정
test: 테스트 추가
chore: 기타 작업