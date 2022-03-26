# JWT-Spring
Spring Boot and Spring Security with JWT including Access and Refresh Tokens 🔑

It is an application that deals with users and their roles (userservice)

The application is connected to a MySQL relational database

### Technologies used
  - Java 11
  - Hibernate
  - Spring
  - Swagger
  - MySQL
  - Maven
  - Docker

## Installation

### With Docker
```
docker-compose up -d
```

### Without Docker
You must have installed :
- JDK 11
- MySQL 8

Your database must be launched.

> You can change database config in `src/main/resources/application.properties`

```
./mvnw package -DskipTests && java -jar target/userservice-0.0.1-SNAPSHOT.jar
```


