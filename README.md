Project Description: Library Management System
This project is a Python-based Library Management System designed to help librarians manage books, students, and transactions effectively. It integrates GUI features using Tkinter, file handling with CSV, and time-based functionalities with datetime.

Features
Book Management:

Add, view, and manage books.
Search books by ID, title, or author.
Check the stock of available books.
Student Management:

Add and manage student information.
Track borrowed books for each student.
Enforce borrowing limits (maximum of 3 books per student).
Transaction Handling:

Issue books to students with a log of issue dates.
Return books with automated penalty calculation for late returns (maximum penalty: $50).
Maintain a detailed transaction log for all activities.
Graphical User Interface:

Easy-to-use interface created with Tkinter.
Separate sections for managing books, students, and transactions.
Data Persistence:

Store book, student, and log data in CSV files (books.csv, students.csv, and logs.csv).
Automatically save and load data upon application start and exit.
How It Works
Book Issue: Checks book availability and student eligibility before issuing. Deducts one copy from stock and logs the transaction.
Book Return: Updates stock, removes the book from the student's borrowed list, calculates penalties, and logs the return.
Search: Quickly locate books or students based on keywords.
Technologies Used
Python Modules:
tkinter: GUI design.
csv: File handling for data storage.
datetime: Issue/return date tracking and penalty calculation.
messagebox: User feedback and error handling.
Usage
Run the Application: python library_management.py

Interacting with the GUI:
Use the search bar to find books or students.
Manage book issue and return operations directly from the interface.
View penalties for late returns.
Limitations
Data storage is limited to CSV files; integration with databases (e.g., SQLite) could improve scalability.
Error handling and input validations could be expanded further.

Future Improvements
Add functionalities to manage book reservations.
Enhance security with user authentication for librarians.
Introduce graphical data visualization for transaction trends.
Migrate to a database for better performance and scalability.
