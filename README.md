# Employee Management System

## Project Overview
The Employee Management System is a backend application developed using Java and Spring Boot to manage employee records. It provides CRUD (Create, Read, Update, Delete) operations through RESTful APIs and stores employee information in a MySQL database.

## Features
- Add new employee records
- View employee details
- Update existing employee information
- Delete employee records
- Database integration using MySQL
- Layered architecture for better code organization

## Technologies Used
- **Programming Language:** Java
- **Backend Framework:** Spring Boot
- **Web Framework:** Spring Web MVC
- **ORM:** Hibernate
- **Persistence:** Spring Data JPA
- **Database:** MySQL
- **Build Tool:** Maven
- **API Testing:** Postman

## Project Architecture

The application follows a layered architecture:

- **Entity Layer:** Represents employee data and database entities.
- **Repository Layer:** Handles database operations using Spring Data JPA.
- **Service Layer:** Contains business logic and processes employee-related operations.
- **Controller Layer:** Handles HTTP requests and REST API endpoints.
- **Application Class:** Main entry point of the Spring Boot application.

## Getting Started

### Prerequisites
- Java Development Kit (JDK)
- MySQL Server
- Maven
- Eclipse IDE or IntelliJ IDEA

### Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Shanvaz06/Employee-Management-System.git
   ```

2. Open the project in your preferred IDE.

3. Create a MySQL database.

4. Configure your database URL, username and password in `application.properties`.

5. Run the main Spring Boot application.

6. Test the REST API endpoints using Postman.

## Project Repository

[Employee Management System – GitHub](https://github.com/Shanvaz06/Employee-Management-System)
