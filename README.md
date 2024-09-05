# Simple Java SQL Server Database Program

This is a basic Java program that connects to a Microsoft SQL Server database. It demonstrates how to create a table, insert data, update data, and query the data using Java's `JDBC` API.

## Features

- Connects to an SQL Server database.
- Creates a `Users` table if it doesn't already exist.
- Inserts sample data into the `Users` table.
- Updates the user data in the table.
- Queries and prints out the data from the table.

## Prerequisites

- Java Development Kit (JDK)**: Make sure you have JDK 8 or higher installed.
- Microsoft SQL Server**: You need a running instance of SQL Server.
- SQL Server JDBC Driver**: Ensure the SQL Server JDBC driver is added to your project's classpath. You can download it [here](https://docs.microsoft.com/en-us/sql/connect/jdbc/download-microsoft-jdbc-driver-for-sql-server).

Configure the database:

This program connects to a SQL Server running on localhost (default port 1433).
The program uses integratedSecurity=true for Windows Authentication. If you are using SQL Server authentication, modify the connection string as needed.
Add the SQL Server JDBC driver:

Download the JDBC driver for SQL Server and include the .jar in your classpath.


##Run the program
javac SimpleDatabaseProgram.java
java SimpleDatabaseProgram



##
