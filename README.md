# ScienceQtech-Employee-Performance-Mapping

ScienceQtech is a startup that works in the Data Science field. ScienceQtech 
has worked on fraud detection, market basket, self-driving cars, supply chain, 
algorithmic early detection of lung cancer, customer sentiment, and the drug 
discovery field. With the annual appraisal cycle around the corner, the HR 
department has asked you (Junior Database Administrator) to generate 
reports on employee details, their performance, and the project that the 
employees have undertaken, to analyze the employee database and extract 
specific data based on different requirements.


Project Description:
 	Creation of Database, ER Diagram.
 	Write a query to fetch required data from database.
 	Write a query to Concatenate and List the data from database.
 	Write a Nested Query & Distribution calculation for database.


Tasks to Perform
Perform the following tasks on the dataset provided using SQL:
1. Create a database named employee, then import data_science_team.csv 
proj_table.csv and emp_record_table.csv into the employee database 
from the given resources
2. Create an ER diagram for the given employee database
3. Write a query to fetch EMP_ID, FIRST_NAME, LAST_NAME, GENDER, and 
DEPARTMENT from the employee record table, and make a list of 
employees and details of their department
Write a query to fetch EMP_ID, FIRST_NAME, LAST_NAME, GENDER, 
DEPARTMENT, and EMP_RATING if the EMP_RATING is:
• less than two
• greater than four
• between two and four
5. Write a query to concatenate the FIRST_NAME and the LAST_NAME of 
employees in the Finance department from the employee table and 
then give the resultant column alias as NAME.
6. Write a query to list only those employees who have someone 
reporting to them. Also, show the number of reporters (including the 
President)
Write a query to list down all the employees from the healthcare and 
finance departments using union. Take data from the employee record 
table.
8. Write a query to list down employee details such as EMP_ID, 
FIRST_NAME, LAST_NAME, ROLE, DEPARTMENT, and EMP_RATING 
grouped by dept. Also include the respective employee rating along 
with the max emp rating for the department.
9. Write a query to calculate the minimum and the maximum salary of the 
employees in each role. Take data from the employee record table.
Write a query to assign ranks to each employee based on their 
experience. Take data from the employee record table.
11. Write a query to create a view that displays employees in various 
countries whose salary is more than six thousand. Take data from the 
employee record table.
12. Write a nested query to find employees with experience of more than 
ten years. Take data from the employee record table.
Write a query to create a stored procedure to retrieve the details of the 
employees whose experience is more than three years. Take data from 
the employee record table
Write a query using stored functions in the project table to check 
whether the job profile assigned to each employee in the data science 
team matches the organization’s set standard
The standard is given as follows:
• Employee with experience less than or equal to 2 years, assign 
'JUNIOR DATA SCIENTIST’
• Employee with experience of 2 to 5 years, assign 'ASSOCIATE DATA 
SCIENTIST’
• Employee with experience of 5 to 10 years, assign 'SENIOR DATA 
SCIENTIST’
• Employee with experience of 10 to 12 years, assign 'LEAD DATA 
SCIENTIST’,
• Employee with experience of 12 to 16 years, assign 'MANAGER'
Create an index to improve the cost and performance of the query to 
find the employee whose FIRST_NAME is ‘Eric’ in the employee table 
after checking the execution plan.
16. Write a query to calculate the bonus for all the employees, based on 
their ratings and salaries (Use the formula: 5% of salary * employee 
rating).
17. Write a query to calculate the average salary distribution based on the 
continent and country. Take data from the employee record table.


