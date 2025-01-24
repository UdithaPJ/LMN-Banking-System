# LMN Banking System

## Overview
The LMN Banking System is a console-based banking application developed in C++. It provides essential banking functionalities, including account management, employee and customer handling, and secure user authentication. This project is designed to simulate real-world banking operations while ensuring data security.

## Features
- **User Authentication:** Secure login system for administrators, employees, and customers.
- **Account Management:** Create and manage both savings and current accounts.
- **Transaction Handling:** Deposit and withdraw money securely.
- **Interest and Overdraft Management:** Set interest rates and overdraft charges.
- **File Management:** Save and load user and account details from files.

## Technologies Used
- **Programming Language:** C++
- **File Handling:** Used for storing user and account data
- **OOP Concepts:** Implemented using classes such as `Bank`, `Administrator`, `Customer`, and `Employee`

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/UdithaPJ/LMN-Banking-System.git
   ```
2. Navigate to the project directory:
   ```sh
   cd LMN-Banking-System
   ```
3. Compile the project using a C++ compiler (g++ or MSVC):
   ```sh
   g++ main.cpp -o banking_system
   ```
4. Run the executable:
   ```sh
   ./banking_system
   ```

## Usage
1. **Login:** Select user type (Admin, Employee, or Customer) and enter credentials.
2. **Administrator Functions:**
   - Add employees
   - Set interest rates
   - Set overdraft charges
3. **Employee Functions:**
   - Add customers
   - Create savings and current accounts
   - Process deposits and withdrawals
4. **Customer Functions:**
   - View balance
   - Perform transactions

## File Management
- `users.txt`: Stores user credentials and types.
- `accounts.txt`: Stores account details including balance and account type.

## License
This project is licensed under the MIT License.

