# Spring Boot REST API Project

## Overview

This is a simple Spring Boot application that demonstrates basic REST API functionality with two endpoints that return string messages.

## Project Structure

The project contains a single controller class `AppController` with two GET endpoints:

```
src/main/java/lk/ac/vau/fas/ict/controller/
└── AppController.java
```

## API Endpoints

### Base URL
All endpoints are prefixed with `/app`

### Available Endpoints

1. **Message Endpoint**
   - `GET /app/msg`
   - Response: `"Hello SpringBoot"`

2. **Name Endpoint**
   - `GET /app/name`
   - Response: `"My name is Spring Boot"`

## Prerequisites

- Java JDK 11 or later
- Maven 3.6.0 or later
- IDE (IntelliJ IDEA, Eclipse, or VS Code recommended)

## Running the Application

1. Clone the repository (if applicable)
2. Build the project:
   ```bash
   mvn clean install
   ```
3. Run the application:
   ```bash
   mvn spring-boot:run
   ```

The application will start on port 8080 by default.

## Accessing the Endpoints

Once the application is running, you can access the endpoints at:
- http://localhost:8080/app/msg
- http://localhost:8080/app/name

## Testing

You can test the endpoints using:
- Browser
- curl:
  ```bash
  curl http://localhost:8080/app/msg
  curl http://localhost:8080/app/name
  ```
- Postman or any API testing tool

## Configuration

This basic application doesn't require any special configuration. The default Spring Boot settings are sufficient.

## Dependencies

The project uses standard Spring Boot Starter Web dependency:
```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-web</artifactId>
</dependency>
```
