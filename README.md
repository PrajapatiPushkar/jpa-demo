# JPA Demo 🚀

A **Spring Boot + Spring Data JPA** demo project to learn and practice working with JPA repositories and CRUD operations in a REST API.

This project shows how to use Spring Data JPA to interact with a database using entities, repositories and services.

---

## 🧠 What You’ll Learn

✔ Basic CRUD (Create, Read, Update, Delete)  
✔ Spring Data JPA repositories  
✔ Entity mapping with JPA annotations  
✔ REST APIs with Spring Boot  
✔ MySQL (or any RDBMS) integration  
✔ Using Spring Boot configuration properties  

---

## 📦 Technologies

- **Java**
- **Spring Boot**
- **Spring Data JPA**
- **Hibernate**
- **MySQL / H2 / other RDBMS**
- **Maven**

---
src
├── main
│ ├── java
│ │ └── com/yourpackage
│ │ ├── controller
│ │ ├── service
│ │ ├── repository
│ │ └── entity
│ └── resources
│ └── application.properties
└── test
# MySQL example
spring.datasource.url=jdbc:mysql://localhost:3306/your_db_name

spring.datasource.username=root

spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true
spring.jpa.database-platform=org.hibernate.dialect.MySQL8Dialect

🧪 Testing

Use Postman or Insomnia to test REST APIs.

Sample JSON
{
  "name": "John Doe",
  "email": "john@example.com"
}

📍 Author

Pushkar Prajapati
B.Tech CSE Student – Building backend skills with Spring Boot

## 📁 Project Structure
