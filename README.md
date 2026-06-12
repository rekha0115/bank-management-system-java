# Bank Management System

## Project Overview

The Bank Management System is a Java-based application developed to manage banking operations such as customer registration, authentication, account management, and financial transactions. The system uses MySQL as the backend database and JDBC for database connectivity.

The application provides separate login portals for Customers, Employees, and Administrators, allowing different users to access functionalities based on their roles. It simulates basic banking operations in a secure and efficient manner through a menu-driven interface.

## Objectives

* To automate basic banking operations.
* To manage customer and employee records efficiently.
* To provide secure login authentication for different user roles.
* To perform account transactions such as deposits and withdrawals.
* To maintain accurate account balances and apply interest calculations.

## Features

### Customer Module

* Customer registration with personal details.
* Secure login using email and password.
* Deposit money into an account.
* Withdraw money after balance verification.
* View current account balance.

### Employee Module

* Employee login using employee credentials.
* Access banking operations based on employee role.

### Admin Module

* Secure administrator login.
* View customer information.
* View employee records.
* Add interest to customer accounts automatically.

### Transaction Management

* Deposit and withdrawal operations.
* Insufficient balance validation for withdrawals.
* Automatic balance updates after each transaction.
* Interest calculation and addition to customer accounts.

## Technologies Used

* Java
* JDBC (Java Database Connectivity)
* MySQL
* SQL

## Database Tables

* Customers
* Employees
* Admin

## Outcome

This project demonstrates the implementation of database connectivity, user authentication, transaction processing, and role-based access control using Java and MySQL. It provides a simplified simulation of real-world banking operations while ensuring data consistency and transaction validation.
