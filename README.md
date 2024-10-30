# ojek_online_backend_golang
This project provides a database structure and data queries for an online OJEK application, designed to meet several specific needs. It allows users to monitor customer, driver, and order data effectively by implementing the Repository pattern.

Features
Monthly Order Total: View total orders each month.
Frequent Customers: Display customers who frequently order within three months (by name).
Popular Areas: Identify areas with high and low order volumes.
Customer Login Status: Check the number of customers logged in or logged out.
Active Drivers: View drivers who actively take orders each month.
Implementation
The application uses the Repository pattern to implement queries effectively. This pattern helps to organize code, making it more modular and maintainable.

Usage
Database Setup: Define tables for Customer, Driver, Order, and Area with relationships to implement the features.
Add Features: Include data entry features for customers, drivers, and orders to facilitate CRUD operations.
Requirements
Database: MySQL / PostgreSQL (or any preferred relational database)
Backend Language: Python (with SQLAlchemy) / Node.js (with Sequelize)
Framework (optional): Flask / Express for API
Getting Started
Clone this repository.
Set up the database schema as described in db_schema.sql.
Implement the repository pattern in your chosen language.
Run the application and test the features.
