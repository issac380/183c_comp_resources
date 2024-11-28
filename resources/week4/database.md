---
title: Database Basics
layout: default
nav_exclude: true
---

# Database Basics

A **database** is where an application stores its data. It is essential for managing and retrieving information like user accounts, product catalogs, and transaction records. For this section, we will focus on Relational Databases

## Relational Databases

Relational databases are a type of database that organizes data into structured tables consisting of rows and columns. Each table represents a specific entity (e.g., users, orders, or products). The Structured Query Language (SQL) takes advantage of the underlying consistency to achieve efficiency with the database operations.

## Common Database Operations

1. **Basic Operations:**
   - **Create:** Add new data (e.g., a new user account).
   - **Read:** Retrieve data (e.g., fetching product details).
   - **Update:** Modify existing data (e.g., changing a user’s email).
   - **Delete:** Remove data (e.g., deleting a user account).

2. **Querying:**
   - SQL Example:
     ```sql
     SELECT * FROM users WHERE age > 25;
     ```

## Example: Displaying User Data

1. **User Action:** A user visits their profile page and logs into their account with id = 123.
2. **Backend Query:**
   - The backend retrieves the user’s data from the database.
3. **Database Query Example:**
   - SQL:
     ```sql
     SELECT name, email, join_date FROM users WHERE id = 123;
     ```

4. **Frontend Display:**
   - The backend sends the retrieved data to the front end to populate the profile page.

Databases are the backbone of any application, enabling efficient storage, retrieval, and management of data.
