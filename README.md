# Digital Bank Project

This project is a web application for managing customers and their accounts. It provides various functionalities such as customer CRUD operations, viewing accounts and operations, and performing financial transactions.

## Technologies Used

- Backend: Spring Boot
- Frontend: Angular
- Database: MySQL

## Features

- User authentication and authorization
- Customer management (Create, Read, Update, Delete)
- Account management (Create, Read, Update, Delete)
- Account operations (Debit, Credit, Transfer)
- Search functionality
- Responsive user interface

## Backend

The backend of the digital bank project is developed using Spring Boot framework. It provides the necessary APIs for managing customers, accounts, and operations.

### API Endpoints

- `/customers`: Handles CRUD operations for customers.
- `/customers/{id}`: Retrieves a specific customer by ID.
- `/accounts`: Handles CRUD operations for accounts.
- `/accounts/{id}`: Retrieves a specific account by ID.
- `/accounts/{id}/operations`: Retrieves operations associated with a specific account.

## Frontend

The frontend of the digital bank project is developed using Angular framework. It provides an intuitive user interface for interacting with the application.

### Screenshots

1. Customers Page: ![Customers Page](/screenshots/1-customers.png)
2. Search Functionality: ![Search Functionality](/screenshots/2-search.png)
3. Add New Customer: ![Add New Customer](/screenshots/3-new-customer.png)
4. Delete Customer: ![Delete Customer](/screenshots/4-delete.png)
5. Accounts Page: ![Accounts Page](/screenshots/5-accounts.png)
6. Debit Operation: ![Debit Operation](/screenshots/6-debit.png)
7. Transfer Operation: ![Transfer Operation](/screenshots/7-transfer.png)

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

This project is licensed under the @MohamedYoussfi.
