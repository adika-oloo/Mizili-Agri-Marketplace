Mizili Agri Database Management System

 Project Title
Mizili Agri: Relational Database for an AgriTech Platform

Description
This project is a complete database design and implementation for *Mizili*, an agriculture and marketplace platform that connects farmers, buyers, and agents. The system supports user management, produce listings, transactions, and logistics—all with proper data integrity and relational design using MySQL.

Key Features
- User roles: Farmers, Buyers, Agents
- Produce listings with categories and prices
- Order and transaction tracking
- Inventory and logistics support
- Fully normalized schema (up to 3NF)
- Strong use of constraints (PK, FK, UNIQUE)

How to Run / Setup

1. Make sure you have MySQL installed (or use MySQL Workbench / XAMPP).
2. Open MySQL Workbench or your terminal.
3. Run the following commands:
```sql
-- Step 1: Create the database
CREATE DATABASE mizili_agri;

-- Step 2: Select it
USE mizili_agri;

-- Step 3: Import the schema
-- Run the `mizili_agri.sql` file from this repo (can be done via UI or CLI)
