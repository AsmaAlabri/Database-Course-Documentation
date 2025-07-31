
# 1. Comparison: Flat File Systems vs Relational Databases

| Feature | Flat File System | Relational Database |
|---------|------------------|---------------------|
| **Structure** | Stores data in a single file (e.g., text file, CSV) with no formal structure other than rows and columns. | Stores data in structured **tables** with rows and columns, managed by a **Database Management System (DBMS)**. |
| **Data Redundancy** | High — same data may appear in multiple files, leading to duplication. | Low — data is normalized to reduce duplication. |
| **Relationships** | No direct support for relationships between different datasets. | Supports relationships between tables using **Primary Keys** and **Foreign Keys**. |
| **Example Usage** | A single CSV file storing customer contact details. | A MySQL database with separate tables for Customers, Orders, and Products. |
| **Drawbacks** | Hard to search, update, and maintain; prone to inconsistencies and errors. | Requires DBMS setup and knowledge; can be complex for small datasets. |


# 2. the mind map that provided in the repo

# 3. Roles in a Database System

In a database project, different roles contribute to designing, developing, and maintaining the database system. Here are the key roles and their typical responsibilities:

- **System Analyst**  
  Analyzes business requirements and determines the database needs to support organizational processes.

- **Database Designer**  
  Designs the logical and physical structure of the database, including tables, relationships, and constraints.

- **Database Developer**  
  Implements the database design by creating tables, writing queries, stored procedures, and triggers.

- **Database Administrator (DBA)**  
  Responsible for database installation, configuration, security, backup, recovery, and performance tuning.

- **Application Developer**  
  Develops software applications that interact with the database to perform operations like data retrieval and updates.

- **Business Intelligence (BI) Developer**  
  Creates reports, dashboards, and analytics tools to help businesses make data-driven decisions.
