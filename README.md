# Grocery Store Management System (SQL)

A SQL-based Grocery Store Management System for storing, querying, and analyzing grocery retail data — products, categories, suppliers, customers, orders, order details, and employees.

*Files included*
- Presentation (PPT/PDF): /mnt/data/Grocery sql ppt.pdf :contentReference[oaicite:4]{index=4}  
- SQL script: /mnt/data/project.sql :contentReference[oaicite:5]{index=5}

---

## Project Overview
This project builds a relational database to manage grocery store operations and demonstrates analysis using SQL queries. It includes:
- A normalized database schema (Categories, Products, Customers, Suppliers, Orders, OrderDetails, Store_Employees)
- An ER diagram and schema visuals in the presentation.
- A collection of analytical SQL queries to derive insights (top customers, product revenues, supplier contributions, order trends, employee performance, etc.)

---

## Quick Start

### Requirements
- MySQL (or compatible RDBMS)
- Basic knowledge of SQL and git

### Load database & run queries
1. Open project.sql and inspect schema, queries, and sample analysis.
2. To execute:
   - Start your MySQL server.
   - Create and use a database (the script includes create database projects; use projects;).
   - Run the SQL script:
     bash
     mysql -u <username> -p < project.sql
     
   - Or run queries manually via your SQL client.

---

## Key Insights
The project answers 25+ questions, such as:
- Unique customers and top customers by spend.
- Product performance: best-sellers, revenue by product & category.
- Monthly & weekday vs weekend order patterns.
- Supplier product counts and revenue contribution.
- Employee order handling and revenue processed.

(Visualizations and sample outputs appear in the PPT /mnt/data/Grocery sql ppt.pdf.) :contentReference[oaicite:6]{index=6}

---

## How to Contribute
1. Fork the repository.
2. Create a branch: git checkout -b feature/my-change
3. Make changes, commit, and push.
4. Open a pull request.

---

## License
Add a license (e.g., MIT) as needed.

---

## Contact
Project prepared by the team. See PPT for group member names and credits. :contentReference[oaicite:7]{index=7}
