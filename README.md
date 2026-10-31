# PixFlow Ledger

Aplicação backend em Spring Boot para o PixFlow Ledger.

## Tecnologias

- Java 21
- Spring Boot 4.1
- Spring Web MVC
- Spring Data JPA
- PostgreSQL
- Maven

## Pré-requisitos

- JDK 21
- PostgreSQL em execução

## Configuração

Configure a conexão com o banco em `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/pixflow_ledger
spring.datasource.username=postgres
spring.datasource.password=postgres
```

## Como executar

```bash
./mvnw spring-boot:run
```

## Testes

```bash
./mvnw test
```

## Build

```bash
./mvnw clean package
java -jar target/pixflow-ledger-0.0.1-SNAPSHOT.jar
```
