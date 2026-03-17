Auth Service - Spring Boot & JWT
This repository contains the Authentication Service component for the Complete Java Full Stack: AWS, Spring Boot, Microservices project. This service handles user authentication and authorization using Spring Security and JWT (JSON Web Tokens).

🚀 Project Overview
This service provides secure endpoints for users to register, log in, and manage their authentication state. It is designed to be part of a microservices architecture.

Key Features
User Registration: Secure password handling.
JWT Authentication: Issuing access tokens for API security.
Refresh Token Mechanism: Long-lived sessions with security.
Authorization: Role-based access control.
Local DB: Uses JSON files to simulate a database for local development (0:6:40:16).
🛠️ Technology Stack
Java 17+
Spring Boot 3.x
Spring Security
JWT (JSON Web Tokens)
JSON (for local data storage)
📋 Project Structure
Controller: Handles incoming requests for auth.
Service: Business logic for managing users and tokens.
Local DB: Simulations of data storage using JSON files.
⚙️ Getting Started
To run this service locally:

Clone the repository.
Build the project using Gradle.
Run the Spring Boot application.
Note: Ensure your application.properties are configured correctly for local development.
