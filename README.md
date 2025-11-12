# ITS4243 – Microservices and Cloud Computing
### Assignment 01 – Part 2 (Student Management REST API)

## Technologies and Tools
- Java 17  
- Spring Boot 3  
- Spring Web  
- Spring Data JPA  
- H2 Database  
- Maven  

## How to Run
1. Open the project in VS Code.  
2. Run the command:
   ```bash
   mvn spring-boot:run
   
Application will start at: http://localhost:8080

## H2 Console

URL: http://localhost:8080/h2-console

JDBC URL: jdbc:h2:mem:studentdb

Username: sa

Password: (empty)

## Test API Endpoints

Use Postman or Swagger UI to test the following endpoints:

Add a new student: POST	- /api/students	
Get all student:s GET - /api/students	
Get student by ID: GET - /api/students/{id}	
Update a student: PUT	- /api/students/{id}	
Delete a student: DELETE - /api/students/{id}

## Developed by:

Name: M.S.Sidhdhika Banu
Index No: ICT/21/814
