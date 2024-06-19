# Demo Project with Spring Boot

## Overview
This project is a demonstration of a web application built with Spring Boot, showcasing basic CRUD operations for user management. It integrates Spring Security for authentication and Spring Data JPA for persistence with MySQL database. The application provides endpoints for user registration and retrieval, demonstrating RESTful principles.

## Features
- **User Registration:** Allows users to register with a unique username, email, and password. Passwords are securely hashed using BCrypt.
- **User Retrieval:** Provides an endpoint to fetch user details based on the username.
- **Error Handling:** Global exception handling to manage unexpected errors and provide appropriate responses.
- **Security:** Integrates Spring Security to secure endpoints and manage user authentication.

## Technologies Used
- **Backend:** Spring Boot, Java 17
- **Database:** MySQL
- **Dependencies:** Spring Boot Starter Web, Spring Boot Starter Data JPA, Spring Boot Starter Security, Springdoc OpenAPI, Lombok, MySQL Connector Java
- **Tools:** Maven

## Getting Started
### Prerequisites
Ensure you have the following installed:
- Java 17
- Maven
- MySQL

## setup the development environment in vs code
1. Install the <strong> Java Extension Pack </strong> extension
2. Install the <strong> Spring Boot Extension Pack </strong> extension 

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/DhirajsGithub/sping-boot-simple-project
   cd demo

2. I already added the mysql database url in the application.properties file. You can change it according to your database url or just use the same database url.

3. Build and Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```

4. Access the Application : 
    ```bash
     http://localhost:8080/swagger-ui.html
    ```
    
5. You can see the swagger documentation of the application. You can test the application from the swagger documentation.
