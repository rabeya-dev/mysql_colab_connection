# mysql_colab_connection
Python and MySQL connection using Google Colab
# MySQL Connection with Python in Google Colab

A beginner-friendly project demonstrating how to install MySQL, create a database, and connect Python to MySQL using `mysql-connector-python` in Google Colab.

## Overview

This project covers the basic workflow of connecting a Python application to a MySQL database in a Google Colab environment.

## Features

- Install and start MySQL Server
- Create a MySQL database and user
- Configure database permissions
- Connect Python to MySQL
- Execute SQL queries using Python
- Display database tables and connection results

## Tech Stack

- Python
- MySQL 8
- Google Colab
- MySQL Connector/Python
- SQL

## Getting Started

### 1. Open the Notebook

Open the notebook in Google Colab and run each cell in order.

### 2. Install Dependencies

```bash
pip install mysql-connector-python
```

Install and start the MySQL Server separately in the Colab environment.

### 3. Create the Database

Create a database named `world` and configure a MySQL user with the required permissions.

### 4. Connect Python to MySQL

Configure the database connection with your own credentials, then execute a test query such as:

```sql
SELECT DATABASE();
```

### 5. Verify the Connection

A successful connection should display the database name and any available tables.

## Project Structure

```text
mysql-colab-connection/
├── README.md
├── mysql_colab_connection.ipynb
├── requirements.txt
└── .gitignore
```

## Important Notes

- This project is intended for learning and experimentation.
- Google Colab runtimes are temporary; database state may not persist after a runtime reset.
- Existing databases and tables may need to be imported into a new runtime.
- Never commit passwords, API keys, or other secrets to GitHub.

## Learning Outcomes

- Basic MySQL administration
- SQL database creation and permissions
- Python database connectivity
- Executing SQL queries from Python
- Organizing and documenting a GitHub project

## License

Add a license if you intend to distribute or reuse this project under specific terms.
