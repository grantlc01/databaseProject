# databaseProject

I was tasked with creating a database for use by a pizzeria in my Database Systems class of Fall 2023. 
This repository contains only three other files, one for creating all of the tables, one for inserting the data into those tables, and one containing the queries to create to test the database.
This project was not completed using git, instead it was uploaded to github later (hence the lack of commits).

All SQL for this project was run in MicroSoft SQL Server (MSS).

Prior to starting the SQL part of the project, I created a complex entity relationship diagram to cover all the things a pizzeria might need to keep track of. This includes a full menu with groups and sub-groups of items, employee types and wages, employee qualifications, customer information, order information, vendors information, and more. Each table had to be carefully thought over during the ERD stage, as the relationships between tables are the most critical aspect the database.

Once the ERD was finished it was simple, yet tedious, to finish. Each table from the ERD was translated over into SQL with data types, primary keys, and foreign keys being the most crucial part to pay attention to (DatabaseCreationQueries.txt). Once the tables had been created in MSS, they would need to be filled with data (DatabaseInsertQueries.txt).

The final step was to create and run some queries assigned to give some outputs that matched what the professor wanted (Step5Queries.txt). 
