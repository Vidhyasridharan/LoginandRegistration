# Login and Registration API (Spring Boot)

A backend service that provides user registration and authentication using Spring Boot and Spring Security.

## Summary
This project demonstrates authentication and security fundamentals including password hashing, custom user authentication, and protected endpoints using Spring Security.

## Key Features
- User registration and login functionality
- Password hashing using BCrypt
- Authentication via custom UserDetailsService
- Session-based authentication with Spring Security
- Secured endpoints with role-based access control support

## Tech Stack
- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- BCrypt
- H2 Database
- Maven

## Security Configuration Highlights
- Form-based login using Spring Security
- Passwords stored securely using BCrypt hashing
- Custom authentication provider backed by application user data
- Protected routes requiring authentication

## Running Locally
```bash
git clone https://github.com/Vidhyasridharan/loginandregistration.git
cd loginandregistration
./mvnw spring-boot:run

Engineering Focus
-Authentication and authorization fundamentals:
-Secure password storage
-Backend security configuration
-Request-level access control

Future Enhancements:
-JWT-based authentication
-Stateless security configuration
-Refresh token support
-Fine-grained role-based authorization
Copy code
