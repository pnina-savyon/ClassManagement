# Class Management System

## Tech Stack

- **Language & Framework**: C#, .NET 7 (ASP.NET Core Web API)
- **Database**: SQL Server, Entity Framework Core (Code First, Migrations)
- **Authentication**: JWT Bearer Authentication, Role-based Authorization
- **Algorithms**: Google OR-Tools (Constraint Solving)
- **API & Tooling**: Swagger (OpenAPI)
- **Development Tools**: Git, GitHub, Visual Studio / VS Code

## Features

- RESTful Web API for class management
- CRUD operations for core entities (students, teachers, classes, seats, surveys)
- Secure API endpoints with JWT authentication and role-based authorization
- Automated seat allocation using constraint solving
- Rule-based and score-based seat allocation logic
- Post-solution analysis of seating results
- Integrated API documentation using Swagger

## How to Run

### Prerequisites
- .NET SDK 7
- SQL Server (local or express)
- Visual Studio or VS Code

### Steps
1. Clone the repository  
2. Configure the database connection string in `appsettings.json`  
3. Apply Entity Framework migrations (if required)  
4. Run the Web API project  
5. Access the API documentation via Swagger  

## Project Status

The core functionality of the system is implemented and operational.  
The project may be extended with additional features and improvements.

## Purpose

This project aims to provide a backend system that supports teachers and students by organizing classroom data and assisting in classroom management processes.

It focuses on data-driven decision making, including automated seat allocation based on constraints and rules, to support an effective learning environment.

## Contributors

- **tamar-mann** – Backend Development, System Design
- **pnina-savyon** – Backend Development, System Design




