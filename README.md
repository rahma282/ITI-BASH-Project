# ITI Bash Shell Script Database Management System (DBMS)

## Project Overview
This project aims to develop a simple **Database Management System (DBMS)** using **Bash shell scripting**. The system allows users to store and retrieve data from the hard disk through a **Command-Line Interface (CLI) menu-based application**.

---



## Features
### Main Menu
- **Create Database**: Create a new database (stored as a directory).
- **List Databases**: List all existing databases.
- **Connect To Database**: Connect to a specific database to perform operations.
- **Drop Database**: Delete a specified database.

### Database Operations (After Connecting to a Database)
- **Create Table**: Create a new table within the connected database.
- **List Tables**: List all tables within the connected database.
- **Drop Table**: Delete a specified table from the connected database.
- **Insert into Table**: Insert a new row of data into a specified table.
- **Select From Table**: Retrieve and display data from a specified table.
- **Delete From Table**: Delete specific rows from a specified table.
- **Update Table**: Update data in a specified table.

---

## Usage Guide
### Main Menu Options
#### **Create Database**
1. Enter the database name.
2. The system will create a directory for the database if it does not already exist.

#### **List Databases**
- Lists all existing databases (directories).

#### **Connect To Database**
1. Enter the database name to connect.
2. Upon successful connection, a new menu for database operations is displayed.

#### **Drop Database**
1. Enter the database name to delete.
2. The system will prompt for confirmation before deleting the database.

### **Database Operations Menu**
#### **Create Table**
1. Enter the table name and the number of columns.
2. Define column names and data types (**int** or **str**).
3. The first column is the **primary key** (int).

#### **List Tables**
- Lists all tables (files) in the connected database.

#### **Drop Table**
1. Enter the table name to delete.
2. The system will prompt for confirmation before deleting the table.

#### **Insert into Table**
1. Enter the table name.
2. Input values for each column.
3. The system validates data types and enforces **primary key uniqueness**.

#### **Select From Table**
- Choose to display the entire table or specific rows based on column values.

#### **Delete From Table**
1. Enter the table name and row number to delete.
2. The system will prompt for confirmation before deleting the row.

#### **Update Table**
1. Enter the table name and **primary key** value of the row to update.
2. Input new values for the columns.
3. The system validates data types.

---

## Technologies Used
- **Bash Shell Scripting**
- **Linux Command-Line Interface (CLI)**
- **File System for Data Storage**

---

## Future Enhancements
- Implementing **user authentication** for database access.
- Supporting more **data types and constraints**.
- Adding **export/import functionality** for tables.
- Enhancing **error handling and logging**.

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone git@github.com:rahma282/ITI-BASH-Project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd DB
   ```
3. Run the script:
   ```bash
   ./menu
   ```
---
   
## Authors
This project was made by two ITI students:

- **Mostafa Lotfy**  
- **Rahma Mostafa**



