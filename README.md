# Spring Boot Hello World Application

This is a simple **Spring Boot** project demonstrating basic REST endpoints.

## 📌 Features
- Built with Spring Boot
- Exposes two REST endpoints:
  - `GET /hello` → returns `"Hello!"`
  - `GET /greet` → returns `"Nice to meet you!"`

## 🗂 Project Structure
```
Directory structure:
└── adrin-bershik-c-j-day7proj1phase1/
    ├── pom.xml
    ├── requests.http
    └── src/
        ├── main/
        │   ├── java/
        │   │   └── com/
        │   │       └── day7proj1phase1/
        │   │           ├── App.java
        │   │           └── helloworld/
        │   │               ├── SpringBootHelloWorldApplication.java
        │   │               └── controller/
        │   │                   └── HelloController.java
        │   └── resources/
        │       └── application.properties
        └── test/
            └── java/
                └── com/
                    └── day7proj1phase1/
                        └── AppTest.java
```

## ▶️ How to Run

### Prerequisites
- Java 17+ (or the version specified in your `pom.xml`)
- Maven installed

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Adrin-Bershik-C-J/day7proj1phase1.git
   cd day7proj1phase1
2. mvn spring-boot:run
3. Access the endpoints
   ### Hello endpoint
GET http://localhost:8080/hello

### Greet endpoint
GET http://localhost:8080/greet

