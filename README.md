# 🏠 Rental Management System

## 📌 Description
The **Rental Management System** is a database-driven application designed to facilitate the management of rental properties, tenants, payments, and maintenance requests. It helps property owners streamline their rental operations while providing tenants with an efficient way to handle their rentals.

## 🚀 Features
- Secure storage of users (property owners & tenants)
- Property registration and management
- Rental tracking and lease agreements
- Payment processing with various status updates
- Maintenance request management

## 🛠️ Setup & Installation
### Step 1: Clone the Repository
git clone https://github.com/Ephantusmr/Rental-Management-System.git
cd Rental-Management-System

Step 2: Import the SQL Schema
Open your MySQL database tool (e.g., MySQL Workbench or command line).

Create a database:
CREATE DATABASE rental_management;
Import the provided SQL file:
mysql -u ephantusmr -p rental_management < rental_management.sql
Step 3: Run Queries
Once the database is set up, you can start querying tables:
SELECT * FROM users;
SELECT * FROM properties;
SELECT * FROM rentals;
SELECT * FROM payments;
SELECT * FROM maintenance_requests;
📷 Entity Relationship Diagram (ERD)
Below is a visual representation of the database schema:
![image](https://github.com/user-attachments/assets/1c5749af-0458-4078-b88a-59ff3ca5ad2f)



💻 Technologies Used
Database: MySQL

Language: SQL

Tools: MySQL Workbench, GitHub

🔗 Repository Structure
rental-management-system/
│── sql/
│   ├── rental_management.sql
│── README.md

🤝 Contributing
Feel free to fork this repository and submit pull requests! Suggestions and improvements are welcome.

