# Employee_Management_System

The Employee Management System is a web application built using the Spring Boot framework, designed to manage employee records. It provides basic CRUD (Create, Read, Update, Delete) operations for employee data. This README provides an overview of the system and instructions for setup and usage.

Features

View Employees: View a list of employees with their first name, last name, and email.
Add Employee: Add a new employee to the system.
Update Employee: Edit and update the details of an existing employee.
Delete Employee: Remove an employee from the system.
Pagination: View employee records in pages with navigation options.

Technologies Used
Spring Boot: A Java framework for building web applications.
Thymeleaf: A Java-based templating engine for dynamic HTML generation.
Hibernate: An Object-Relational Mapping (ORM) tool for interacting with the database.
MySQL: The relational database used to store employee records.

Setup
Clone the Repository: Clone this repository to your local machine using Git:

git clone https://github.com/your-username/employee-management-system.git
Database Configuration:

Create a MySQL database for the application.

Update the database connection settings in the application.properties file to match your database configuration:

spring.datasource.url=jdbc:mysql://localhost:3306/your_database
spring.datasource.username=your_username
spring.datasource.password=your_password
Build and Run:

Build and run the application using Maven:

cd employee-management-system
mvn spring-boot:run
Access the Application:

Open a web browser and navigate to http://localhost:8080/ to access the Employee Management System.

Usage
View Employees: Upon accessing the application, you'll see a list of employees. You can navigate through pages and sort the records by clicking on column headers.

Add Employee: Click the "Add Employee" button to create a new employee record. Fill in the details and click "Save" to add the employee.

Update Employee: Click the "Update" button next to an employee to edit their information. Make your changes and click "Save" to update the record.

Delete Employee: Click the "Delete" button next to an employee to remove them from the system.

Pagination: Navigate between pages to view more employees.

