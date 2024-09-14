# Bank Management System

## Overview

This Bank Management System is a command-line application that allows users to perform various operations related to managing bank accounts. The system supports opening new accounts, making transactions, displaying account details, deleting accounts, viewing balances, updating account details, and generating transaction graphs.

## Features

- **Open an Account**: Allows users to create a new bank account with personal details and initial deposit.
- **Transaction**: Perform transactions related to the account.
- **Display Account Details**: View details of an existing account.
- **Delete an Account**: Remove an account from the system.
- **View Balance**: Check the current balance of the account.
- **Change Details**: Update personal details associated with the account.
- **Graph**: View a graphical representation of transaction history.
- **Exit**: Exit the application.

## Requirements

- Python 3.x
- PostgreSQL database
- Required Python packages:
  - `psycopg2` (for PostgreSQL database connectivity)
  - `validate_email_address` (for email validation)
  - `verify_email` (for email verification)
  - `matplotlib` (for plotting graphs)
  - `numpy` (for handling numerical operations)

## Installation

1. **Clone the repository**:
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Install required packages**:
    ```bash
    pip install psycopg2 validate_email_address verify_email matplotlib numpy
    ```

3. **Set up PostgreSQL**:
   - Ensure PostgreSQL is installed and running.
   - Create a database named `Bank_management` and configure it with the required tables. The application expects a database with tables for account details and login details.

4. **Configure the Database Connection**:
   - Update the database connection parameters in the `Account` class if necessary.


## Example

- To open a new account, choose option `1` from the menu and provide the requested information.
- To view a transaction graph, choose option `7` and enter your account number.

## Notes

- Ensure that the PostgreSQL server is running and accessible.
- The email sending functionality requires proper configuration of the SMTP server, which is not included in this script.



