Library Management System (SQL Server)
An end-to-end SQL project demonstrating database design, management, and security implementation for a library environment.
## Project Overview
This repository contains a structured T-SQL script for the Library_DB. The project covers the full lifecycle of database management, from schema creation and data manipulation to advanced security roles and backup strategies.
## Key Features Implemented
1. Data Structure (DDL)
• Tables: Created Members, Books, and Borrowings.
• Constraints: Implemented PRIMARY KEY, FOREIGN KEY, UNIQUE, and NOT NULL to ensure data integrity.
2. Data Operations (DML)
• Populating Data: Inserted sample records for members, books, and borrowing transactions.
• Data Maintenance: Included UPDATE and DELETE scripts for real-world scenarios.
3. Security & Access Control (DCL)
• Roles: Created librarian and reader users.
• Permissions: * librarian: Full access to manage members and view data.
• reader: Read-only access to browse the library collection.
4. Maintenance & Recovery
• Complete Backup and Restore scripts to ensure data availability and disaster recovery.
## Technical Stack
• Engine: Microsoft SQL Server
• Tool: SQL Server Management Studio (SSMS)
• Language: T-SQL
## How to Run
1.	Download the Library_Management_System.sql file.
2.	Open it in SSMS.
3.	Create a folder at C:\Backup\ (required for the backup script).
4.	Execute the script to build the entire environment.

Developed by: Muhira Mohammed
