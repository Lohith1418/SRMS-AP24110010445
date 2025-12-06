# SRMS-AP24110010445
This project is a role-based Student Management System developed in C using file handling for permanent data storage. The system uses two files: credentials.txt to store login information and user roles, and students.txt to maintain student records.

The program starts with a secure login system that allows only three attempts. Based on the logged-in user’s role—Admin, Staff, or Guest—the system displays different menus and access permissions. Admins can add, update, delete, search, and view student records. Staff members can search and display data, while Guests are limited to viewing and searching records.

Student details are stored in a text file, and update/delete operations use a temporary file to ensure data accuracy. The program follows a modular structure with separate functions for each task, making the system organized, simple to follow, and easy to maintain.
