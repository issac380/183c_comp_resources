---
title: Backend Overview
layout: default
nav_exclude: true
---

# Backend Overview

The **backend** is the part of a web application that users don’t directly see. It handles the logic, processes requests from the front end, and communicates with the database.

## Key Features of a Backend

1. **Request Processing:**
   - When a user interacts with the front end (e.g., clicks a button), the backend processes the request.
   - Example: A user submits a login form. The backend verifies their credentials.

2. **Logic:**
   - Implements the rules and functionality of the application.
   - Example: In an e-commerce app, the backend calculates the total price of items in the cart, including taxes and discounts.

3. **Data Communication:**
   - Acts as a bridge between the front end and the database.
   - Example: The backend retrieves a user’s order history from the database and sends it to the front end for display.


## Common Backend Technologies

- **Languages:** Python, Node.js (JavaScript), Ruby, Java, PHP.
- **Frameworks:**
  - Python: Django, Flask.
  - Node.js: Express.js.
  - Ruby: Ruby on Rails.


## Example Backend Flow

1. A user searches for "laptops" on an e-commerce website.
2. The request is sent to the backend via an API endpoint like `/search`.
3. The backend queries the database for matching items.
4. The results are returned to the front end and displayed to the user.


## Example: A Login System

1. **User Action:** A user enters their email and password on a login form.
2. **Backend Logic:**
   - The backend receives the credentials.
   - It queries the database for a matching email and verifies the password.
3. **Response:**
   - If valid, the backend generates a session token and sends it to the user.
   - If invalid, it sends an error message.

The backend serves as the core logic processor, ensuring the application functions correctly and securely.
