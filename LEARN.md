
# Digital Bank Project


This project is a web application for managing customers and their accounts. It provides various functionalities such as customer CRUD operations, viewing accounts and operations, and performing financial transactions.

## Technologies Used

- Backend: Spring Boot
- Frontend: Angular
- Database: MySQL

## Features

- User authentication and authorization
- Customer management (Create, Read, Update, Delete)
- Account management (Search)
- Account operations (Debit, Credit, Transfer)
- Search functionality
- Responsive user interface

## Backend

The backend of the digital bank project is developed using the Spring Boot framework. It provides the necessary APIs for managing customers, accounts, and operations.

### API Endpoints

- `/customers`: Handles CRUD operations for customers.
- `/customers/{id}`: Retrieves a specific customer by ID.
- `/accounts`: Handles CRUD operations for accounts.
- `/accounts/{id}`: Retrieves a specific account by ID.
- `/accounts/{id}/operations`: Retrieves operations associated with a specific account.

## Frontend

The frontend of the digital bank project is developed using the Angular framework. It provides an intuitive user interface for interacting with the application.


## Getting Started

To run the digital bank project locally, follow these steps:

1. Clone the repository.
2. Set up the backend:
   - Install Java and Maven.
   - Configure the MySQL database connection in the `application.properties` file.
   - Build and run the Spring Boot application.
3. Set up the frontend:
   - Install Node.js and npm.
   - Install Angular CLI globally.
   - Install project dependencies using `npm install`.
   - Configure the backend API endpoint in the environment file.
   - Build and run the Angular application using `ng serve`.
4. Access the application in your browser at `http://localhost:4200`.

## License

This project is licensed under MIT

