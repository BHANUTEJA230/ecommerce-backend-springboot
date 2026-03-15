# E-Commerce Backend System

## Overview

The **E-Commerce Backend System** is a RESTful backend application designed to manage core functionalities of an online shopping platform.
The project is developed using **Java and Spring Boot** and provides APIs for managing products, users, and orders.
It demonstrates backend development concepts such as layered architecture, database integration, and REST API design.

---

## Tech Stack

* **Java**
* **Spring Boot**
* **Spring Data JPA**
* **MySQL**
* **Maven**
* **Postman** (API testing)
* **Git & GitHub**

---

## Features

* Product management (Create, Read, Update, Delete)
* RESTful API architecture
* Database integration with MySQL
* Modular backend design
* API testing using Postman

---

## Project Structure

src/main/java/com/ecommerce

controller – Handles REST API requests
service – Contains business logic
repository – Handles database operations and database queries
entity – Defines database models

---

## API Endpoints

**POST /products**
Add a new product

**GET /products**
Retrieve all products

**PUT /products/{id}**
Update product details

**DELETE /products/{id}**
Delete a product

---

## Database

The application uses **MySQL** for persistent data storage.
Spring Data JPA is used for ORM and database interaction.

Example Product Fields:

* id
* name
* description
* price
* quantity

---

## Tools Used

* IntelliJ IDEA / VS Code
* MySQL Workbench
* Postman
* Git
* GitHub

---

## Future Enhancements

* JWT Authentication
* User registration and login system
* Shopping cart module
* Order management system
* Payment gateway integration

---

## Project Status

This project is currently under development and will be expanded with additional modules and features.

---

## Author

Developed as a backend learning project to practice **Java, Spring Boot, REST APIs, and database integration**.
