# Spring Boot Maven HelloWorld API

This is a simple Spring Boot project created as a first exercise with Spring Boot and Maven.

## Features
✅ API REST with two GET endpoints:
- `/HelloWorld?name=YourName`  
  Returns: `Hello, YourName. You are running a Maven project.`  
  (If `name` is not provided, defaults to `UNKNOWN`)

- `/HelloWorld2` or `/HelloWorld2/YourName`  
  Returns: `Hello, YourName. You are running a Maven project.`  
  (If no name is provided, defaults to `UNKNOWN`)

## ✅ Runs on port `9000` (configured in `application.properties`).

## ✅ Built with:
- Spring Boot 3.5.3
- Maven
- Java 11+

## How to run
```bash
mvn spring-boot:run
