
# Library Management System

## Overview
The Library Management System is a comprehensive web application designed to manage library operations efficiently, it provides a user-friendly interface for librarians and patrons to handle book inventories, author details, editorial information, user accounts, loan tracking, and return management. The system is built with a modular architecture, separating the backend API from the frontend MVC application for scalability and maintainability.

## Features
- **Book Management**: Add, update, delete, and search books with details like title, ISBN, publication year, and genre.
- **Author Management**: Maintain author profiles and link them to their published works.
- **Editorial Management**: Track publishing houses and their associated books.
- **User Management**: Handle user registrations, roles (e.g., admin, member), and authentication.
- **Loan and Return Tracking**: Record book loans, due dates, and returns with fine calculations.
- **Country and Fee Management**: Support for international authors and configurable fee structures.
- **Responsive Web Interface**: Intuitive MVC-based frontend for easy navigation and operations.
- **RESTful API**: Backend API for programmatic access and potential integrations.

## Tech Stack
- **Backend**: ASP.NET Core Web API with Entity Framework Core for data persistence.
- **Frontend**: ASP.NET Core MVC with Razor views, CSS, and JavaScript.
- **Database**: SQL Server (via Entity Framework migrations).
- **Architecture**: Repository pattern for data access, layered services for business logic.
- **Development Tools**: Visual Studio, .NET SDK.

## Getting Started

### Technologies
- .NET 6.0 or later
- SQL Server (or compatible database)
- Visual Studio 2022 or VS Code

## Project Structure
- Library: Backend API project with controllers, models, repositories, and services.
- BookHive: Frontend MVC project with views and controllers.
- `Migrations/`: Database schema changes.
- README.md: This file.
