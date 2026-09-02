# 📚 Library Management System

A simple and efficient **Library Management System** developed using **Python and Pandas**.  
The system uses CSV files as a lightweight database to manage books, students, and book issue/return records.

This project demonstrates fundamental concepts of **Python programming, file handling, data management, Pandas DataFrames, functions, conditional statements, and CRUD-like operations**.

---

## 🚀 Project Overview

Managing books and issue/return records manually can be time-consuming and error-prone.

This project provides a simple **command-line based Library Management System** that allows users to:

- Add new books
- Display available books
- Search for books
- Issue books to students
- Return issued books
- Automatically update book quantities
- Store data permanently using CSV files

The system is designed to be simple, lightweight, and easy to understand for students learning Python and data management.

---

## ✨ Features

### 📖 1. Add Book

Allows the user to add a new book by entering:

- Book ID
- Book Title
- Author Name
- Quantity

The book information is stored in `books.csv`.

---

### 📋 2. Display Books

Displays all books currently stored in the library database.

Example:

```text
------ BOOK LIST ------

  Book_ID              Title              Author  Quantity
0    B001       Python Basics       John Smith         5
1    B002  Data Structures         Robert Brown         3
