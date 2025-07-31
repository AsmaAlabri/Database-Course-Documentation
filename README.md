
# 1. Comparison: Flat File Systems vs Relational Databases

| Feature | Flat File System | Relational Database |
|---------|------------------|---------------------|
| **Structure** | Stores data in a single file (e.g., text file, CSV) with no formal structure other than rows and columns. | Stores data in structured **tables** with rows and columns, managed by a **Database Management System (DBMS)**. |
| **Data Redundancy** | High — same data may appear in multiple files, leading to duplication. | Low — data is normalized to reduce duplication. |
| **Relationships** | No direct support for relationships between different datasets. | Supports relationships between tables using **Primary Keys** and **Foreign Keys**. |
| **Example Usage** | A single CSV file storing customer contact details. | A MySQL database with separate tables for Customers, Orders, and Products. |
| **Drawbacks** | Hard to search, update, and maintain; prone to inconsistencies and errors. | Requires DBMS setup and knowledge; can be complex for small datasets. |
