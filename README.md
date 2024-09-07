# Banking Application

This is a Spring Boot-based Banking Application that allows users to create accounts, deposit and withdraw funds, and manage account details. The frontend is implemented using HTML, CSS, and JavaScript, while the backend uses Spring Boot for handling the business logic.

## Features

- **Create Account**: Allows users to create a new bank account with an initial balance.
- **Get Account**: Retrieve the details of a specific account using the account ID.
- **Deposit**: Deposit funds into an account.
- **Withdraw**: Withdraw funds from an account.
- **Delete Account**: Delete an account from the system.
- **List All Accounts**: Retrieve a list of all active accounts.

## Technology Stack

- **Backend**: Spring Boot, Java
- **Frontend**: HTML, CSS, JavaScript
- **Database**: (Specify your database, e.g., H2, MySQL, PostgreSQL, etc.)
- **Tools**: Eclipse/VS Code

## API Endpoints

| Method   | Endpoint               | Description                     |
|----------|------------------------|---------------------------------|
| `POST`   | `/api/accounts`         | Create a new account            |
| `GET`    | `/api/accounts/{id}`    | Get account details by ID       |
| `PUT`    | `/api/accounts/{id}/deposit`  | Deposit amount into account     |
| `PUT`    | `/api/accounts/{id}/withdraw` | Withdraw amount from account    |
| `DELETE` | `/api/accounts/{id}`    | Delete account by ID            |
| `GET`    | `/api/accounts`         | Get a list of all accounts      |

## Prerequisites

- Java 11+
- Maven
- Spring Boot
- A database (H2, MySQL, or any other)

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/banking-app.git
    ```

2. Navigate to the project directory:
    ```bash
    cd banking-app
    ```

3. Install dependencies and build the project:
    ```bash
    mvn clean install
    ```

4. Run the application:
    ```bash
    mvn spring-boot:run
    ```

5. The application will start on `http://localhost:8080`.

## Usage

- Open a web browser and navigate to `http://localhost:8080`.
- Use the provided forms to create accounts, deposit/withdraw money, and view account details.

## Frontend

The frontend consists of simple forms to interact with the API. The HTML form submits data for creating accounts, depositing, withdrawing, and other operations. 

## Contributing

Feel free to fork this repository, open issues, and submit pull requests.


