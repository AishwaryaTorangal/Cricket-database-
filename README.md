# CricketDB

**CricketDB** is a simple Java-based application designed for managing cricket team records in an Oracle database. This console application provides a user-friendly interface for performing CRUD (Create, Read, Update, Delete) operations on a table named `team`.

## Features

- **Create Table:** 
  - Create a new `team` table in the Oracle database with fields for:
    - Team ID
    - Team Name
    - Coach Name
    - Captain Player ID
    - City

- **Insert Record:** 
  - Insert new records into the `team` table with validation checks to ensure data integrity.

- **Update Record:** 
  - Update existing records in the `team` table, including modifications to:
    - Team Name
    - Coach Name
    - Captain Player ID
    - City

- **Delete Record:** 
  - Delete records from the `team` table based on the Team ID.

- **Display Records:** 
  - Retrieve and display all records from the `team` table, providing a comprehensive view of the stored data.

## Technology

- **Java:** Developed using Java.
- **JDBC:** Utilized for communication with the Oracle database.

## Error Handling

Includes mechanisms to manage common exceptions such as SQL errors and invalid input formats.

## Purpose

This project demonstrates the practical application of Java programming and database management concepts. It serves as an educational example for implementing basic database operations and offers a foundational tool for managing cricket team data.

## Future Enhancements

The modular structure of the application allows for easy maintenance and potential future enhancements.


