# 📚 Book Service — Spring Boot Microservice

A simple, modular Spring Boot microservice designed to manage books. This service is part of a growing portfolio of backend microservices built to demonstrate clean architecture, testability, and production-ready engineering practices.

---

## ✨ Features

- REST-ready Spring Boot application structure
- Domain model for representing books
- Layered architecture (controller → service → model → repository)
- Maven wrapper included for consistent builds
- H2 in-memory database for fast local development
- Clean project layout following industry conventions

---

## 📁 Project Structure

| Path | Description |
|------|-------------|
| `book-service/` | Root project folder |
| `src/main/java/com/example/book_service/BookServiceApplication.java` | Spring Boot entry point |
| `src/main/java/com/example/book_service/model/Book.java` | Domain model |
| `src/main/java/com/example/book_service/service/` | Service layer |
| `src/main/java/com/example/book_service/service/dto/` | DTOs (will appear once added) |
| `src/main/resources/application.properties` | Spring Boot configuration |
| `src/test/java/com/example/book_service/BookServiceApplicationTests.java` | Test suite |

---

## 🛠 Technologies Used
- Java 17+
- Spring Boot
- Maven
- H2 Database
- JUnit 5

## ▶️ Running the Application
Using Maven Wrapper:
```bash
./mvnw spring-boot:run
```
---

Or run BookServiceApplication directly from IntelliJ.

## ✅ Testing
Run the full test suite:
```bash
./mvnw test
```
---

## 🗺 Roadmap
- Add BookDto and mapping layer
- Implement REST endpoints (CRUD)
- Add persistence with Spring Data JPA
- Add validation and error handling
- Add integration tests
- Add Docker support
- Add API documentation (Swagger/OpenAPI)

## 📄 License
This project currently has no license. You may add one later if you want to open‑source it.

