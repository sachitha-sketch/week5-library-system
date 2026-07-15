# Library Management System

**Author:** Sachitha

## Overview

The **Library Management System** is a Python application developed using **Object-Oriented Programming (OOP)** principles. It allows librarians to manage books and members, borrow and return books, search the library catalog, track overdue books, and save data using JSON files.

This project uses only the **Python Standard Library** and demonstrates modular programming, file handling, exception handling, and class-based design.

---

# Features

* Add new books
* Remove books
* Register new members
* Borrow books
* Return books
* Search books by:

  * Title
  * Author
  * ISBN
* View available books
* View overdue books
* Library statistics
* JSON data storage
* Automatic data loading
* Backup functionality
* Menu-driven interface
* Unit testing using `unittest`

---

# Project Structure

```text
week5-library-system/
│
├── library_system/
│   ├── __init__.py
│   ├── book.py
│   ├── member.py
│   ├── library.py
│   └── main.py
│
├── data/
│   ├── books.json
│   ├── members.json
│   └── backup/
│
├── tests/
│   ├── test_book.py
│   ├── test_member.py
│   └── test_library.py
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Requirements

* Python 3.10 or later
* No external libraries required

---

# Installation

Clone the repository:

```bash
git clone https://github.com/your-username/week5-library-system.git
```

Move into the project directory:

```bash
cd week5-library-system
```

---

# Running the Program

From the project root:

```bash
python library_system/main.py
```

If using package execution:

```bash
python -m library_system.main
```

---

# Running the Tests

Run all tests:

```bash
python -m unittest discover tests
```

Or run an individual test file:

```bash
python -m unittest tests.test_book
python -m unittest tests.test_member
python -m unittest tests.test_library
```

---

# Sample Menu

```text
========================================
      LIBRARY MANAGEMENT SYSTEM
========================================

1. Add New Book
2. Register Member
3. Borrow Book
4. Return Book
5. Search Books
6. View All Books
7. View Members
8. View Overdue Books
9. Library Statistics
10. Save Data
0. Exit
```

---

# Technologies Used

* Python
* Object-Oriented Programming (OOP)
* JSON
* File Handling
* Exception Handling
* unittest

---

# Future Improvements

* Graphical User Interface (GUI)
* Barcode support
* Fine calculation
* Email reminders for overdue books
* Database integration (SQLite/MySQL)
* User authentication
* Book reservation system

---

# License

This project is created for educational purposes and may be modified or extended as needed.
# week5-library-system
