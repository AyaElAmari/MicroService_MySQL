# Microservice Project with MySQL

This GitHub repository demonstrates a microservices architecture implemented with Spring Boot, MySQL, Eureka Server, and Gateway.

## Services

### 1. Eureka Server
- Manages service registration and discovery.
- **URL:** [http://localhost:8761](http://localhost:8761)

### 2. Gateway
- Serves as the entry point for accessing microservices.
- **URL:** [http://localhost:8888](http://localhost:8888)

### 3. Car Service
- Handles interactions with a MySQL database related to car data.
- **URL:** [http://localhost:8089](http://localhost:8089)

### 4. Client Service
- Manages interactions with a MySQL database containing client-related data.
- **URL:** [http://localhost:8088](http://localhost:8088)

## Project Setup

### Prerequisites
Make sure you have the following tools installed before setting up the project:

- **Java Development Kit (JDK):** Ensure that Java is installed on your system.
- **Docker:** Required for running MySQL containers.
- **Maven:** Used for building the project.
