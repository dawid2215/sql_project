📚 Library Management System (SQL Project)
This is a comprehensive SQL-based Library Management System developed using MySQL. The project simulates the essential operations of a real-world library, including managing books and members, issuing and returning books, tracking status, and performing data analysis for managerial insights. The objective is to showcase skills in relational database design, SQL query development, and data analytics.

🗂 Project Structure
📋 Database Schema
The database design consists of normalized relational tables with appropriate primary and foreign keys, and constraints. The main tables are:

🏢 branch: stores information about library branches

👩‍💼 employees: includes library staff such as clerks, assistants, and managers

📇 members: registered users of the library

📚 books: inventory of books available in the library

📖 issued_status: records details of books issued to members

🔄 return_status: records details of returned books

🔄 CRUD Operations
Implemented full Create, Read, Update, and Delete functionality such as:

➕ Adding new books and members

✏️ Updating member details

❌ Deleting issued book records

🔍 Retrieving issued books data by employee or member

🧠 Advanced SQL Queries
Supports complex queries, including:

👥 Finding members who have borrowed multiple books

📂 Grouping books by category

🧑‍💼 Identifying employees under specific branch managers

🆕 Listing members registered within the last 180 days

📊 Data Analytics and Business Insights
Generates insightful reports and analyses, including:

💰 Total rental income grouped by book category

📈 Most frequently issued books

🚫 Books that have not yet been returned

💵 Filtering books above a specified rental price

🗃 Creation of summary tables using “Create Table As Select” (CTAS) for issued counts and pricing filters

🛠 Tools and Technologies
MySQL: Relational database management system

SQL: Query language

ER Modeling: For database design

Use of joins, subqueries, aggregation, and constraints for advanced querying

✅ Skills Demonstrated
Relational database design and normalization

Application of primary and foreign key constraints

Writing efficient SQL queries including joins, subqueries, and aggregates

Date filtering and use of built-in SQL functions

Data transformation and summary table creation

Business logic implementation via queries

🎯 Use Cases Covered
Adding new library books, members, and employees

Tracking book issuance and returns along with employee involvement

Generating follow-up reports on unreturned books

Reporting by branch, employee, or member metrics

Analyzing rental income by book category

💼 How This Project Adds Value for Employers
Demonstrates ability to:

Design and build relational data systems from the ground up

Work with real-world data relationships and constraints

Perform complex SQL operations and aggregations

Extract actionable insights from structured data

Implement business logic in a database context
