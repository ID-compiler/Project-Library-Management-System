# Project-Library-Management-System
# Spring Boot CRUD Application - Books and Authors

This project is a Spring Boot application designed to manage information for two entities: **Books** and **Authors**. It supports Create, Read, and Update operations using JSP views and a MySQL database.

## 📌 Features

- Add new Books and Authors using a form
- Display all Books and Authors in a list view
- Update existing Book and Author records
- Perform an inner join to fetch books with their corresponding authors
- Layered architecture with MVC pattern
- Styled JSP views for user interaction

## 📁 Technologies Used

- Java 17+
- Spring Boot
- Spring Data JPA
- JSP
- JSTL
- MySQL
- Maven

## 🧱 Project Structure

- `model/` - Entity classes: `Book`, `Author`
- `repository/` - JPA repositories for data access
- `service/` - Business logic
- `controller/` - Spring MVC controllers
- `webapp/WEB-INF/jsp/` - JSP views

## 📊 Database

- MySQL used to persist data
- Entities:
  - `Book (id, title, isbn, author_id)`
  - `Author (id, name, email)`
- Relationship: One-to-Many (Author → Books)

