# 🏫 Spring JDBC Student Management System

A simple **Student Management System** using **Spring JDBC Template** and **MySQL**.

## Features
- Insert new student record
- View all students
- Update student record
- Delete student record

## Database
```sql
CREATE DATABASE db2;
USE db2;
CREATE TABLE studnet (
  rno INT PRIMARY KEY,
  name VARCHAR(50),
  marks DOUBLE
);
```

## Run Instructions
1. Configure `App1.xml` with your MySQL username/password.
2. Compile and run `Test.java`.
3. Use console menu for operations.

## Requirements
- JDK 8+
- Spring Framework jars
- MySQL Database
