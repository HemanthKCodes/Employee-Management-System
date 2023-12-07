# Employee Management System

This is a simple Employee Management System built with a Spring Boot backend and a React frontend.

## Table of Contents

- [Overview](#overview)
- [Frontend Code](#frontend-code)
  - [Installation](#installation)
  - [Usage](#usage)
- [Backend Code](#backend-code)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation-1)
  - [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Employee Management System allows you to perform basic CRUD operations on employee records. The frontend is built with React, and the backend is a Spring Boot application.

## Frontend Code

### Installation

1. Navigate to the frontend directory:

   ```bash
   cd frontend
   ```

2. Install dependencies:

    ```bash
    npm install
    ```

### Usage

Start the React application:

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser to interact with the Employee Management System.

## Backend Code

### Prerequisites

- Java Development Kit (JDK)
- Maven

### Installation

Navigate to the backend directory:

```bash
cd backend
```
Build the project:

```bash
mvn clean install
```

Run the Spring Boot application
```bash
java -jar target/employee-management-system.jar
```

## API Endpoints

- **GET /api/v1/employees:** Get all employees.
- **POST /api/v1/employees:** Create a new employee.
- **GET /api/v1/employees/{id}:** Get employee by ID.
- **PUT /api/v1/employees/{id}:** Update an existing employee.
- **DELETE /api/v1/employees/{id}:** Delete an employee by ID.

## Contributing

Contributions are welcome! If you find any issues or have suggestions, feel free to open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
