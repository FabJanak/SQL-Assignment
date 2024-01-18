# SQL Assignment

## Installation

Follow the installation steps in the video tutorial: [SQL Installation Tutorial](https://www.youtube.com/watch?v=Sfvpgu9ID2Q)

## Learn SQL

For learning SQL basics, refer to this tutorial: [SQL Basics Tutorial](https://www.youtube.com/watch?v=hlGoQC332VM)

## SQL Overview

**SQL (Structured Query Language):**
SQL is a domain-specific language used for managing and manipulating relational databases. It provides commands to interact with databases, enabling tasks such as querying data, updating records, and managing database structure.

### SQL Commands

SQL commands are categorized into different types:

- **DDL (Data Definition Language):**
  - `CREATE`: Create a database or its objects (table, index, function, views, store procedure, and triggers).
    ```sql
    CREATE TABLE table_name (
      column1 datatype,
      column2 datatype,
      ...
    );
    ```
  - `DROP`: Delete objects from the database.
    ```sql
    DROP TABLE table_name;
    ```
  - `ALTER`: Alter the structure of the database.
    ```sql
    ALTER TABLE table_name
    ADD column_name datatype;
    ```
  - `TRUNCATE`: Remove all records from a table.
    ```sql
    TRUNCATE TABLE table_name;
    ```

- **DML (Data Manipulation Language):**
  - `INSERT`: Insert data into a table.
    ```sql
    INSERT INTO table_name (column1, column2, ...)
    VALUES (value1, value2, ...);
    ```
  - `UPDATE`: Update existing data within a table.
    ```sql
    UPDATE table_name
    SET column1 = value1, column2 = value2, ...
    WHERE condition;
    ```
  - `DELETE`: Delete records from a database table.
    ```sql
    DELETE FROM table_name
    WHERE condition;
    ```

- **Other Commands:**
  - `SHOW DATABASES`: Display a list of all available databases on the server.
    ```sql
    SHOW DATABASES;
    ```
  - `USE`: Select a specific database to work with.
    ```sql
    USE database_name;
    ```
  - `SHOW TABLES`: List all tables in the currently selected database.
    ```sql
    SHOW TABLES;
    ```
  - `DESC` or `DESCRIBE`: Provide information about the structure of a table.
    ```sql
    DESCRIBE table_name;
    ```

## Assignment Questions

### Execute the following instructions:

1. show databases ;
2. create database _______ ;
3. use ________ ;
4. show tables ;
5. create table _______ ;
6. desc _______ ;

### For the table(s) you have created do the following:
1. Insert a column
2. delete a column
3. rename a column
4. change the data type of a column
5. make a column primary key / remove primary key


## Note⚠️: Your submission would be considered once you complete the assignment in Readme.md and commit it.
This readme.md file provides a clear guide for installation, learning resources, SQL overview, and instructions for the assignment questions
