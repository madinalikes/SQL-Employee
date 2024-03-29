# SQL
Importing CSV files into a SQL database, and then working with those data. Performing data modeling, data engineering, and data analysis.

#### Challenge Instructions


This project utilizes Data Engineering and Data Analysis to build a SQL database of employees of a corporation called Pewlett Hackard from the 1980s and 1990s. There are six CSV files holding the data of employees. The SQL tables were designed and the data in the CSVs were successfully imported into a SQL database.

#### Data Engineering
---
Inspect the CSVs and sketch out an ERD of the tables. The QuickDBD was used in this project. Use the information from ERD to create a table schema for each of the six CSV files and specify data types, primary keys, foreign keys, and other constraints.

For the primary keys check to see if the column is unique, otherwise create a composite key, which takes two primary keys in order to uniquely identify a row

Be sure to create tables in the correct order to handle foreign keys


<img width="333" alt="ERD" src="https://user-images.githubusercontent.com/111404552/209611094-572df7f1-9b45-4c82-b816-38ca754aa8f7.png">


#### Data Analysis

List the following details of each employee: employee number, last name, first name, sex, and salary

List first name, last name, and hire date for employees who were hired in 1986

List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name

List the department of each employee with the following information: employee number, last name, first name, and department name

List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B"

List all employees in the Sales department, including their employee number, last name, first name, and department name

List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name

