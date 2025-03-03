# Student-Data-Manager
# Student Management System 🎓

This is a **Student Management Data Management System**, a full-stack web application built using **Spring Boot** and **HTML**. It helps manage student records, including registration, updates, and data retrieval.

## 📌 Features
✔️ Add, Edit, and Delete Students  
✔️ Search and Filter Student Records  
✔️ RESTful API with Spring Boot  
✔️ User Authentication (Upcoming)  

## 🛠️ Tech Stack
- **Backend:** Spring Boot, Spring MVC, Spring Data JPA  
- **Database:** MySQL / PostgreSQL  
- **Frontend:** HTML(optional)  
- **Tools:** Maven, Thymeleaf  

## 🚀 Getting Started
### 1️⃣ Clone the Repository

2️⃣ Configure Database (MySQL)
Update application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/student_db
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update

3️⃣ Run the Application
sh
Copy
Edit
mvn spring-boot:run

4️⃣ Open in Browser
Go to: http://localhost:8080/students

