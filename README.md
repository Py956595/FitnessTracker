# FitBuddy

FitBuddy is a workout tracker app made with Spring Boot

## What's inside

The project uses the following technologies:

Backend:
- Java 11
- Spring Boot with Spring Security and Spring Data JPA
- RESTful API
- Lombok
- SQL
- Maven

Frontend:
- Bootstrap 5 with Bootstrap Icons
- HTML, CSS and JavaScript

## Features

- Users can register and login to the application.
- Users can create their custom exercises.
- Users can log their workout by adding their own custom exercises to a specific date.

## Installation

The project is created with Maven, so you just need to import it to your IDE and build the project to resolve the dependencies.

Maven Wrapper included in the project, you can start the app with: `mvnw spring-boot:run` without installing Maven.

Alternatively, you can start the project with Maven: `mvn spring-boot:run`

## Running the application

A default user with some preloaded data is added at the start of the application.

```
username: user
password: user
```

## Data Storage

It uses an in-memory (H2) database to store the data.

To view and query the database you can browse to /console, eg.: http://localhost:8080/console

Login details:

```
spring.datasource.url=jdbc:h2:mem:db
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=admin
spring.datasource.password=admin
```

## Endpoints

*TODO*