# sql-agent-project

# Multi-Agent SQL Assistant

A multi-agent system that translates natural language into SQL queries, shows the generated SQL to the user, and executes it on a SQLite database. The system maintains session-based memory to track confirmed SQL queries during the current session.

## Features
- Translate natural language questions into SQL queries automatically.
- Show SQL queries to the user before execution.
- Execute SQL on a sample SQLite database with products, customers, and orders tables.
- Maintain short-term memory for session-based interactions.
- Supports session continuity in interactive queries.

## Demo
The Kaggle notebook demonstrates:
- Listing all products with categories.
- List all customers and total sales for each.
- Calculating total sales per customer and per category.

You can view and run the notebook here: [Kaggle Notebook](https://www.kaggle.com/code/arezoodarvishi/natural-language-to-sql-shop-agent)  

GitHub repository: [https://github.com/arezoo-drv/sql-agent-project](https://github.com/arezoo-drv/sql-agent-project)

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/arezoo-drv/sql-agent-project.git
