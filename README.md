# ☕ Cafeteria Management System

A web-based **Cafeteria Management System** developed to simplify and digitize cafeteria operations such as user registration, login, menu management, food ordering, bill generation, and customer feedback.

The system provides separate functionalities for **customers and administrators**, making cafeteria management more organized, efficient, and user-friendly.

---

## 📌 Project Overview

The Cafeteria Management System is a PHP and MySQL-based web application designed to reduce the dependency on manual cafeteria operations.

Customers can register themselves, log in to the system, view available food items, place orders, and submit feedback. The administrator can manage registered users, food items, and orders through an administrative dashboard.

The system stores user, food-item, order, billing, and feedback information in a centralized MySQL database.

---

## ✨ Features

### 👤 User Features

- User Registration
- User Login
- Secure Session-Based Authentication
- Cafe User Registration
- Browse Available Food Items
- Place Food Orders
- Select Item Quantity
- Automatic Bill Generation
- View Order/Bill Summary
- Submit Feedback
- Contact Us Page
- Logout Functionality

### 🛠️ Admin Features

- Admin Login
- Admin Dashboard
- View Registered Users
- Add New Users
- Remove Users
- View Available Food Items
- Add New Food Items
- Remove Food Items
- View Customer Orders
- Manage Cafeteria Records

---

## 🧩 System Modules

### 1. Authentication Module

Provides user registration and login functionality.

- Sign Up
- Login
- Logout
- Session Management
- Admin Authentication

### 2. User Management Module

Stores and manages customer information such as:

- Username
- First Name
- Last Name
- Contact Number
- Date of Birth
- Age
- Address

### 3. Menu Management Module

The system allows the administrator to manage cafeteria food items.

Each item contains information such as:

- Item ID
- Item Name
- Description
- Price

### 4. Online Ordering Module

Customers can:

1. Browse available food items
2. Select required items
3. Enter quantity
4. Place an order
5. Generate a bill

### 5. Billing Module

After an order is placed, the system calculates the order amount and generates a bill summary.

### 6. Feedback Module

Registered users can submit feedback regarding their cafeteria experience.

### 7. Admin Dashboard

The administrator can manage:

- Users
- Food Items
- Orders
- Cafeteria records

---

## 🛠️ Technologies Used

| Category | Technology |
|----------|------------|
| Frontend | HTML |
| Styling | CSS |
| Client-Side Scripting | JavaScript |
| Backend | PHP |
| Database | MySQL |
| Database Connectivity | PHP MySQLi |
| Web Server | Apache |
| Local Development | XAMPP |
| Version Control | Git & GitHub |

---

## 🗄️ Database

The application uses **MySQL** as its database.

The project uses the following major tables:

- `signup_table` – Stores registered login credentials
- `Cafeuser` – Stores customer information
- `Items` – Stores cafeteria food items
- `OrderTable` – Stores customer orders
- `Bill` – Stores billing information
- `feedback` – Stores customer feedback

The database used by the application is:

```text
cafeteria
