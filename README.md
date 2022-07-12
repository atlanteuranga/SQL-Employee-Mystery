# Using SQL to Analyze Employee Data
Employee Database: A Mystery in Two Parts


Background

It is a beautiful spring day, and it is two weeks since you have been hired as a new data engineer at Pewlett Hackard. Your first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.
In this assignment, you will design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. In other words, you will perform:


1. Data Engineering

2. Data Analysis

## Results

Data Modeling
ERD of Tables in the Database before queries

![ERD of Database](ERD.png)

Data Engineering


Use the information you have to create a table schema for each of the six CSV files. Remember to specify data types, primary keys, foreign keys, and other constraints.

[Data Engineering Schema](schema.sql)



Data Analysis
Once you have a complete database, do the following:


1. List the following details of each employee: employee number, last name, first name, sex, and salary.

![Screenshot 1](Screenshots/1.png)


2. List first name, last name, and hire date for employees who were hired in 1986.

![Screenshot 2](Screenshots/2.png)

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

![Screenshot 3](Screenshots/3.png)

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

![Screenshot 4](Screenshots/4.png)

5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

![Screenshot 5](Screenshots/5.png)

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

![Screenshot 6](Screenshots/6.png)

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

![Screenshot 7](Screenshots/7.png)

8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

![Screenshot 8](Screenshots/8.png)



