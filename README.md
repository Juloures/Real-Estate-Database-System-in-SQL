# Real Estate Database System

This project is a SQL-based database system designed to manage real estate properties, clients, agents, and transactions for a real estate agency. It provides functionalities for property listings, client and agent management, as well as purchase and rental transactions.

## Project Overview

The database includes the following tables:
- **Propriedades (Properties):** Stores information about properties, including address, type, value, and status (available, sold, rented).
- **Clientes (Clients):** Contains client information such as name, phone number, email, and interest type (purchase or rental).
- **Agentes (Agents):** Stores real estate agents' details such as name, phone number, and email.
- **Transações (Transactions):** Records real estate transactions, linking clients, agents, and properties. It also captures transaction type (purchase or rental) and transaction dates.

### Database Operations

1. **Property Management:**
   - List available properties.
   - Update property status after a transaction (sold/rented).
   - Delete properties no longer available.

2. **Client and Agent Management:**
   - Insert new clients and agents into the database.
   - Update client details.
   - Remove clients who are no longer interested.

3. **Transaction Management:**
   - Record transactions linking clients, agents, and properties.
   - Query transaction details using `JOIN` to get comprehensive views of each transaction.

### Key Features
- **Data Integrity:** Relationships between clients, agents, and properties are maintained using foreign keys.
- **Efficient Querying:** SQL queries allow for efficient data retrieval, including joins between multiple tables.
- **Easy Maintenance:** The database structure ensures easy addition of new properties, clients, and agents.

### Installation

To run this project, you need a SQL server (such as MySQL) installed. Import the provided SQL scripts to create and populate the database.

1. **Create the database:**
   ```sql
   CREATE DATABASE Imobiliaria;
   USE Imobiliaria;
