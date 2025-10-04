# Spring Boot Todo API

A simple REST API built with Spring Boot.

## Prerequisites
- Java 17+ (check with `java -version`)
- Maven (wrapper is included)

## Run the app
```bash
./mvnw spring-boot:run


The app will start on: http://localhost:8080

Test API

Get all todos:

curl http://localhost:8080/todos

curl -X POST http://localhost:8080/todos -H "Content-Type: application/json" -d "\"Learn Spring Boot\""


