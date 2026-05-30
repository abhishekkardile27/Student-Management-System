Student Management System

A full-stack web application developed using Java Spring Boot, Spring Data JPA, Hibernate, Thymeleaf, and MySQL to manage student records efficiently. The system provides complete CRUD (Create, Read, Update, Delete) operations, allowing administrators to add, view, update, and remove student information through a user-friendly web interface.

🚀 Features
Add new student records
View all students in a structured table
Update existing student details
Delete student records
Responsive web interface using Thymeleaf
Database integration with MySQL
MVC architecture implementation
Spring Data JPA for database operations
Hibernate ORM for object-relational mapping
🛠️ Technology Stack
Backend
Java 21
Spring Boot
Spring MVC
Spring Data JPA
Hibernate
Frontend
Thymeleaf
HTML5
CSS3
Bootstrap
Database
MySQL
Build Tool
Maven
📂 Project Structure
src/main/java
│
├── controller
│   └── StudentController.java
│
├── entity
│   └── Student.java
│
├── repository
│   └── StudentRepository.java
│
├── service
│   └── StudentService.java
│
└── serviceImpl
    └── ServiceImpl.java

src/main/resources
│
├── templates
│   ├── index.html
│   ├── new_student.html
│   └── update_student.html
│
└── application.properties
📋 Functionalities
Student Management
Create student profiles
Store student details in MySQL database
View all registered students
Edit student information
Remove student records
Database Operations
Save student data
Fetch all students
Find student by ID
Update student information
Delete student records
🗄️ Database Schema
Student Table
Column	Type
id	INT (Primary Key)
name	VARCHAR
email	VARCHAR
course	VARCHAR
⚙️ Installation & Setup
Clone Repository
git clone https://github.com/your-username/student-management-system.git
Navigate to Project
cd student-management-system
Configure Database

Update application.properties

spring.datasource.url=jdbc:mysql://localhost:3306/studentManagement
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
Run Application
mvn spring-boot:run
Access Application
http://localhost:8080
🎯 Learning Objectives

This project demonstrates:

Spring Boot Application Development
MVC Architecture
CRUD Operations
Spring Data JPA
Hibernate ORM
Thymeleaf Template Engine
MySQL Database Integration
Dependency Injection
Maven Project Management
