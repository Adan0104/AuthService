# Auth Service - Spring Boot & JWT

This repository contains the Authentication Service component for the Complete Java Full Stack: AWS, Spring Boot, Microservices project. This service handles user authentication and authorization using Spring Security and JWT (JSON Web Tokens).

🚀 Project Overview

This service provides secure endpoints for users to register, log in, and manage their authentication state. It is designed to be part of a microservices architecture.

Key Features
1. User Registration: Secure password handling.
2.  JWT Authentication: Issuing access tokens for API security.
3.  Refresh Token Mechanism: Long-lived sessions with security.
4.  Authorization: Role-based access control.
5.  Local DB: Uses JSON files and MySQL to simulate a database for local development.

🛠️ Technology Stack: Java 17+, Spring Boot 3.x, Spring Security, JWT (JSON Web Tokens), JSON, MySQL (local database)

📋 Project Structure
1. Controller: Handles incoming requests for auth.
2. Service: Business logic for managing users and tokens.
3. Local DB: Simulations of data storage using JSON files.

⚙️ Getting Started
To run this service locally:
1. Clone the repository.
2. Build the project using Gradle.
3. Run the Spring Boot application.
4. Note: Ensure your application.properties are configured correctly for local development.
