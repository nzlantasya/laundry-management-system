# Laundry Management System

A console-based laundry management system developed using Python and MySQL. This application was created to manage customer data, laundry packages, and transaction records through a menu-driven interface.

## Features

* User Login Authentication
* Forgot Password Functionality
* Customer Management (Create, Read, Update, Delete)
* Package Management (Create, Read, Update, Delete)
* Transaction Management (Create, Read, Update, Delete)
* Search Functionality
* Automatic Price Calculation
* Estimated Completion Date Calculation

## Technologies Used

* Python
* MySQL
* mysql-connector-python

## Database Design

The system uses four main tables:

* Users
* Customers
* Packages
* Transactions

The database is designed using relational concepts with foreign key relationships between tables.

## Security Assessment

As a continuation of the project, a security assessment was conducted using the CIA Triad framework.

Key findings included:

* Plaintext password storage
* Authentication security weaknesses
* Security improvement recommendations

The assessment also explored password hashing implementation and network traffic analysis.

## Screenshots

### Login Page

User authentication interface.

### Customer List

Customer data management and record viewing.

### Password Hashing Implementation

Security improvement after CIA Triad analysis.

### Database Structure

Overview of the relational database structure.

### Transaction Records (Database View)

Example transaction data stored in the system database.

## Learning Outcomes

* Python application development
* Relational database design
* CRUD operation implementation
* MySQL integration
* Authentication system development
* Security analysis using CIA Triad

## Repository Structure

```text
main.py
laundryy.sql
README.md
screenshots/
documentation/
```
