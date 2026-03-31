# Spring Boot REST API Project

## 📌 Overview
This project is a backend RESTful API developed using **Spring Boot**.  
It demonstrates how to design and implement a clean, scalable server-side application using modern Java technologies.

The system manages core entities (such as products and orders) and follows a layered architecture to ensure maintainability and separation of concerns.

---

## 🚀 Features
- RESTful API architecture
- Full CRUD operations (Create, Read, Update, Delete)
- Layered design:
  - Controller layer (API endpoints)
  - Service layer (business logic)
  - Repository layer (data access)
- Exception handling and validation
- Integration with database using Spring Data JPA
- Clean and modular project structure

---

## 🛠 Technologies
- Java
- Spring Boot
- Spring Data JPA
- Maven
- REST API
- H2 / SQL Database

---

## 📁 Project Structure
src/
 ├── main/
 │   ├── java/
 │   │   └── com.example.restapp/
 │   │        ├── controller/
 │   │        ├── service/
 │   │        ├── repository/
 │   │        ├── model/
 │   │        └── exception/
 │   └── resources/
 │        └── application.properties

---

## ▶️ Getting Started

### 1. Clone the repository
git clone https://github.com/14mohamad/spring-boot-rest-api-project.git

### 2. Navigate to project directory
cd spring-boot-rest-api-project

### 3. Run the application
./mvnw spring-boot:run

Or run directly from your IDE (IntelliJ / VS Code).

---

## 📬 Example API Endpoints

| Method | Endpoint        | Description            |
|--------|----------------|------------------------|
| GET    | /products      | Get all products       |
| GET    | /products/{id} | Get product by ID      |
| POST   | /products      | Create a new product   |
| PUT    | /products/{id} | Update product         |
| DELETE | /products/{id} | Delete product         |

*(Adjust endpoints based on your actual implementation)*

---

## 🧪 Testing
You can test the API using:
- Postman
- Thunder Client (VS Code)
- Browser (for GET requests)

---

## 📈 Future Improvements
- Add Swagger for API documentation
- Add authentication (JWT / Spring Security)
- Add unit and integration tests
- Connect to a production database (MySQL / PostgreSQL)

---

## 🎯 Purpose
This project was developed as part of a **Full Stack / Server-Side course**  
to practice backend development using Spring Boot and RESTful APIs.

---

## 👨‍💻 Author
Mohamad Mousa  
GitHub: https://github.com/14mohamad