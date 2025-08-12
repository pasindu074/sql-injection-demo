# SQL Injection Demo
A simple PHP + MySQL project to demonstrate how SQL Injection works and how to prevent it.

##Folder Structure

│
├── vulnerable.php       # Vulnerable login/search
├── secure.php           # Secure version with prepared statements
├── db.sql               # Sample database with fake users
├── style.css            # Simple styling
└── README.md            # Documentation

# SQL Injection Demo

A simple PHP + MySQL project to demonstrate how SQL Injection works and how to prevent it.

## Features
- Vulnerable version (uses raw queries)
- Secure version (uses prepared statements)
- Sample fake user database

## Setup
1. Import `db.sql` into MySQL:
   ```bash
   mysql -u root -p < db.sql
