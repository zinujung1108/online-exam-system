ONLINE EXAM SYSTEM

1. INTRODUCTION

This project is an Online Exam System developed as a university project.

The system allows users to register, log in, manage their accounts, take online exams, and view exam results.

2. MAIN FEATURES

User registration

User login

User account management

Question management

Exam management

Online examination

Automatic grading

Exam result viewing

User authentication and authorization

3. TECHNOLOGIES

Java 17

Spring Boot 2.7.1

Spring Data JPA

Spring Security

Thymeleaf

MySQL

Maven

XAMPP

4. REQUIREMENTS

Java 17 or higher

Maven

MySQL

XAMPP

An IDE such as IntelliJ IDEA, Eclipse, or Spring Tool Suite

5. INSTALLATION

Step 1

Clone the project from GitHub.

git clone https://github.com/zinujung1108/online-exam-system.git

Step 2

Open XAMPP.

Start Apache and MySQL if needed.

Step 3

Open phpMyAdmin.

Create a database with the following name.

web_tn_v1

Step 4

Import the SQL file included in the project into the web_tn_v1 database.

Step 5

Open the file application.properties located in

src/main/resources/application.properties

Check the database configuration.

spring.datasource.url=jdbc:mysql://localhost:3306/web_tn_v1
spring.datasource.username=root
spring.datasource.password=

If your MySQL account has a password, change the password value accordingly.

6. RUN THE PROJECT

Open the project with your IDE.

Find the main Spring Boot application class.

Run the application.

After the application starts successfully, open the following address in your browser.

http://localhost:8080

7. PROJECT STRUCTURE

src

main

java

resources

application.properties

templates

static

pom.xml

.gitignore

README.md

8. DATABASE

Database name

web_tn_v1

The project uses MySQL as the database.

XAMPP can be used to run MySQL and manage the database through phpMyAdmin.

9. SECURITY

The project uses Spring Security for user authentication and authorization.

10. PROJECT PURPOSE

This project was developed for educational purposes.

The main purpose is to practice Java, Spring Boot, database management, web application development, and user authentication.

11. AUTHOR

Zinujung1108
