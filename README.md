# Creating-Database-ERD-Entity-Relationship-Diagram-With-PostgreSQL-Coffee-Case

In this scenario, you have recently been hired as a Data Engineer by a New York based coffee shop chain that is looking to expand nationally by opening a number of franchise locations. As part of their expansion process, they want to streamline operations and revamp their data infrastructure.

Your job is to design their relational database systems for improved operational efficiencies and to make it easier for their executives to make data driven decisions.

Currently their data resides in several different systems: Accounting software, suppliers' databases, point of sales (POS) systems, and even spreadsheets. You will review the data in all of these systems and design a central database to house all data. You will then create the database objects and load them with source data. Finally, you will create subsets of data that your business partners require, export them, and then load them into staging databases that use different RDBMS.

Grading criteria
There are a total of 40 points possible for this final project.

Your final assignment will be graded by your peers who are also completing this assignment within the same session. Your grade will be based on the following tasks:

1. Task 1: Identify entities (4 pts)
2. Task 2: Identify attributes (4 pts)
3. Task 3: Create an ERD using the pgAdmin ERD Tool (4 pts)
4. Task 4: Normalize tables (4 pts)
5. Task 5: Define keys and relationships (4 pts)
6. Task 6: Create database objects by generating and running the SQL script from the ERD Tool (4 pts)
7. Task 7: Create a view and export the data (4 pts)
8. Task 8: Create a materialized view and export the data (4 pts)
9. Task 9: Import data into a MySQL database using phpMyAdmin GUI tool (4 pts)
10. Task 10: Import data into a MySQL database (4 pts)

you will use PostgreSQL Database, MySQL. 
These are all relational database management systems (RDBMS) designed to store, manipulate, and retrieve the data efficiently.

In this project, you will be working with a subset of data from the Coffee shop sample data.

You will use a modified version of the data for the project, so to succeed in the project, download the linked files when prompted in the instructions. You do not need to use any data from the source.

In your scenario, you will be working with data from the following sources:

1. Staff information held in a spreadsheet at headquarters (HQ)
2. Sales outlet information held in a spreadsheet at HQ
3. Sales data output as a CSV file from the POS system in the sales outlets
4. Customer data output as a CSV file from a custom customer relationship management system
5. Product information maintained in a spreadsheet exported from your supplier's database

After completing this lab, you will be able to:

1. Identify entities
2. Identity attributes
3. Create an entity relationship diagram (ERD) using the pgAdmin ERD tool
4. Normalize tables
5. Define keys and relationships
6. Create database objects by generating and running the SQL script from the ERD tool
7. Create a view and export the data
8. Create a materialized view and export the data
9. Import data into a MySQL database using phpMyAdmin GUI tool
