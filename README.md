# Multi-Threaded Bank Management & Audit System

[![Java Version](https://img.shields.io/badge/Java-17%2B-blue.svg)](https://www.oracle.com/java/)
[![Build System](https://img.shields.io/badge/Build-Maven-red.svg)](https://maven.apache.org/)
[![Database](https://img.shields.io/badge/Database-MySQL-orange.svg)](https://www.mysql.com/)

A comprehensive Command-Line Interface (CLI) application built with Core Java and JDBC. This project implements key enterprise patterns (Singleton, DAO, Async Logging) while providing complete coverage of Core Java fundamentals, Object-Oriented Programming (OOP), Multithreading, Exceptions, Collections, I/O Streams, and JDBC database operations.

---

## Technical Features & Syllabus Coverage

### 1. Java Introduction & Flow Control
- **Variables & Data Types:** Primitive types (`double`, `int`), Reference types (`String`, `Account`).
- **Operators:** Arithmetic (`+=`), Comparison (`==`), Logical (`&&`), and Type Evaluation (`instanceof`).
- **Control Flow:** `switch-case` menus, `while` execution loops, enhanced `for-each` iterations, and standard console I/O using `java.util.Scanner`.

### 2. Object-Oriented Programming (OOP)
- **Abstraction & Interfaces:** Defined operational contracts using the `AccountOperations` interface and abstract `Account` base class.
- **Inheritance & Polymorphism:** Extended via `SavingsAccount` featuring dynamic method overriding and overloading.
- **Advanced Class Structures:** Implementations of Enums with constructors (`AccountType`), Singleton design pattern (`BankDatabase`), Java Reflection API, and key terms (`this`, `super`, `final`).

### 3. Exception Handling & Multithreading
- **Robust Exception Model:** Custom checked exception (`InsufficientFundsException`), multi-catch blocks, and `try-catch-finally` resource handling.
- **Thread Management:** Asynchronous execution using `Runnable` (`AsyncAuditLogger`), thread life-cycle controls (`sleep`, `join`), and `synchronized` thread safety.

### 4. Collections Framework & I/O Streams
- **Data Structures:** Dynamic management using `ArrayList` and transaction rollback tracking using `Stack`.
- **Arrays:** Processing 1-D arrays and 2-D Jagged Arrays for multi-day transaction ledger analysis.
- **File I/O:** Character-oriented streams (`BufferedWriter`, `FileWriter`) for logging and Byte-oriented streams (`FileOutputStream`) for binary snapshots.

### 5. Database Connectivity with JDBC
- Dynamic loading of JDBC driver (`com.mysql.cj.jdbc.Driver`).
- Connection management via `DriverManager.getConnection()`.
- Safe SQL execution using `PreparedStatement` to protect against SQL injection.
- Externalized database property mapping (`db.properties`).

---

## Prerequisites

Before running the application, ensure your environment meets the following requirements:

- **Java Development Kit (JDK):** Version 17 or higher (`java -version`)
- **Apache Maven:** Version 3.8+ (`mvn -version`)
- **MySQL Database Server:** Version 8.0+ (`mysql --version`)

---

## Database Setup

1. Open your terminal or MySQL Workbench.
2. Log into your MySQL server:
   ```bash
   mysql -u root -p
