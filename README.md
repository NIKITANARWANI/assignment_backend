# Assignment

This is a sample project for managing user signup and login functionality using Spring Boot.

## Prerequisites

- Java 17
- Maven
- Database (e.g., MySQL, PostgreSQL, H2)

## Getting Started

Clone the repository: git clone https://github.com/your-username/assignment.git
Update the database configuration: Open src/main/resources/application.properties. Adjust the database connection information (URL, username, password) based on your setup.

Access the application: The application will be running on http://localhost:8080. Interact with the endpoints using an API testing tool, such as Postman.

Endpoints Signup URL: http://localhost:8080/signup equals POST request type. Request body is JSON object with the following fields name, username, password User mobile and date of birth response will be “Sign up successful” if user creation process completed successfully; otherwise it will display message stating for example that given email address already used.

Login URL: http://localhost:8080/login Method type: POST Request body : JSON object with the following fields username_ User’s user name password –User’s pass swords Response – A JWT if login is successful; otherwise “ Invalid credentials”.

Authorization The application uses JWT based authentication. The /signup endpoint is unauthenticated. All other endpoints require authentication.

Databases The application stores user data in a database. Change the application.properties for database connection to connect to your database account.

Dependencies: Spring Boot Web, Spring Boot Data JPA H2 Database (for development/testing) and 3.

Contributing Contributions are welcome! If you discover problems or have ideas about what can be done better, please open an issue or submit a pull request.