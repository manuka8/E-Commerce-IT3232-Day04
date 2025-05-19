

**SPRING BOOT STARTER - "Kickstart your REST API journey with Spring Boot!"**

Welcome to a minimal yet powerful Spring Boot application designed to get you up and running with RESTful endpoints in no time. Whether you're a beginner exploring Spring or a pro looking for a quick testbed—this starter project has your back!

---

**FEATURES**

* Lightweight & easy to understand
* RESTful API endpoints using Spring Web
* Zero configuration required
* Ready for customization and scaling

---

**PROJECT STRUCTURE**

src
└── main
├── java
│   └── lk.ac.vau.fas.ict
│       └── controller
│           └── AppController.java
└── resources
└── application.properties

---

**HOW TO RUN**

**Prerequisites:**

* Java 17 or later
* Maven 3.x
* IDE (IntelliJ, Eclipse) or terminal access

**Run the App using Maven:**
./mvnw spring-boot\:run

Or run it from your IDE using the main application class.

---

**AVAILABLE ENDPOINTS**

GET    /app/msg    - Returns a greeting message ("Hello SpringBoot")
GET    /app/name   - Returns the name of the app ("My name is Spring Boot")

Test using your browser or tools like Postman or curl:
curl [http://localhost:8080/app/msg](http://localhost:8080/app/msg)
curl [http://localhost:8080/app/name](http://localhost:8080/app/name)

---

**CONFIGURATION**

The app runs on port 8080 by default.
To change the port, edit the `application.properties` file:

server.port=9090

---

**DEPENDENCIES (pom.xml)**

<dependencies>  
    <dependency>  
        <groupId>org.springframework.boot</groupId>  
        <artifactId>spring-boot-starter-web</artifactId>  
    </dependency>  
</dependencies>

---

**WHAT’S NEXT?**

* Add more endpoints and controllers
* Connect to a database (e.g., MySQL, PostgreSQL)
* Add Swagger/OpenAPI for API documentation
* Package as a Docker container

---

