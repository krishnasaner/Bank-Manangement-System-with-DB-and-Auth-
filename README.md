# Bank Management System

A secure and scalable application for managing customer accounts, transactions, balance inquiries, and admin-level oversight. Built with Python and backed by PostgreSQL or SQLite, the system integrates user authentication, role-based access control, and a robust database schema.

## Overview

This Bank Management System is designed to simulate core banking operations through a clean CLI or basic GUI. It supports multiple user roles, enforces authentication, and maintains transactional integrity. Ideal for learning backend system design, database interaction, and secure user authentication.

## Key Features

- **User Authentication**
  - Secure login and registration flow
  - Password hashing and input validation
  - Session management or token-based auth

- **Account Management**
  - Create, view, update, and delete accounts
  - Role-based permissions (Admin/User)

- **Transaction Handling**
  - Deposit, withdrawal, and fund transfer
  - Real-time balance updates with rollback support
  - Transaction history tracking

- **Database Integration**
  - PostgreSQL or SQLite as the primary data store
  - Structured schema with normalization
  - Uses raw SQL queries or ORM (e.g., SQLAlchemy)

- **Admin Dashboard (CLI/GUI)**
  - Monitor all user accounts and transactions
  - View system logs and summaries

## Tech Stack

| Layer         | Technology Used         |
|---------------|--------------------------|
| Language      | Python                   |
| Database      | PostgreSQL / SQLite      |
| Interface     | Command-line (CLI) or Tkinter (GUI) |
| Auth System   | Custom implementation with hashed passwords |
| Deployment    | Local execution, cross-platform support |



