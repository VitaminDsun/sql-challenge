# sql-challenge
homework 9
to start this assignment I was asked to create a -ERD- (Entity Relationship Diagram) this created the tables I will be useing in pgadmin, and this also allowed me to create the columns and establish primary keys foreign keys or (PK's and FK's) this allowed to connections from each of these tables. Once this is done the ERD can be exported to pgadmin and used with databases, there I was asked to list certin detail from the tables after imputing some CSV's such as first name, last name, hire date for certain dates, departments, and other employee information.  

















Unit 9 Homework: Employee Database

Background
It’s a beautiful spring day, and it’s been two weeks since you were hired as a new data engineer at Pewlett Hackard. Your first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remains of the database of employees from that period are six CSV files.
In this assignment, you will design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. In other words, you will perform data modeling, data engineering, and data analysis.

Before You Begin


Create a new repository for this project called sql-challenge. Do not add this homework assignment to an existing repository.


Clone the new repository to your computer.


Add your files to this folder.


Push these changes to GitHub.



Instructions
This assignment is divided into three parts: data modeling, data engineering, and data analysis.

Data Modeling
Inspect the CSVs and sketch out an ERD of the tables. Feel free to use a tool like http://www.quickdatabasediagrams.com.

Data Engineering


Use the provided information to create a table schema for each of the six CSV files. Remember to specify data types, primary keys, foreign keys, and other constraints.


For the primary keys, verify that the column is unique. Otherwise, create a composite key, which takes two primary keys to uniquely identify a row.


Be sure to create tables in the correct order to handle foreign keys.




Import each CSV file into the corresponding SQL table.

Hint: To avoid errors, be sure to import the data in the same order that the tables were created. Also remember to account for the headers when importing.




Data Analysis
Once you have a complete database, perform these steps:


List the following details of each employee: employee number, last name, first name, sex, and salary.


List first name, last name, and hire date for employees who were hired in 1986.


List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.


List the department of each employee with the following information: employee number, last name, first name, and department name.


List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."


List all employees in the Sales department, including their employee number, last name, first name, and department name.


List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.


List the frequency count of employee last names (i.e., how many employees share each last name) in descending order.


Unit 9 Homework Rubric

https://docs.google.com/document/d/1OksnTYNCT0v0E-VkhIMJ9-iG0_oXNwCZAJlKV0aVMKQ/edit
