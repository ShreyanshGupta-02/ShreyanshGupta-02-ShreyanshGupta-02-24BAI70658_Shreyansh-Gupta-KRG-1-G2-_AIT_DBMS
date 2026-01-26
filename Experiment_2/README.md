# Experiment 2 – SQL SELECT Queries with WHERE, GROUP BY, HAVING, ORDER BY

## Experiment
Experiment 2: Understanding and implementing SQL SELECT queries using WHERE, ORDER BY, GROUP BY, and HAVING clauses to retrieve and manipulate data efficiently from relational database tables.

## Aim
The aim of this experiment is to practice writing SQL SELECT statements with filtering, grouping, sorting, and aggregate functions to analyze data from relational tables.

## Objective
- To practice writing SQL SELECT statements.  
- To apply filtering conditions using the WHERE clause.  
- To sort query results using the ORDER BY clause.  
- To group records using the GROUP BY clause.  
- To filter grouped data using the HAVING clause.  
- To analyze data using aggregate functions like COUNT(), SUM(), AVG(), MIN(), and MAX().

## Software Requirements
- Database: Oracle XE or PostgreSQL (PgAdmin)

## Practical / Experiment Steps
1. Display the department name and the average salary of employees for each department.  
2. Consider only those employees whose salary is greater than 20,000.  
3. Display only those departments where the average salary is greater than 30,000.  
4. Arrange the final output in descending order of average salary.

## Procedure of the Experiment
1. Start the system and log in to the computer.  
2. Open the required database tool (Oracle XE or PgAdmin).  
3. Connect to the database containing the EMPLOYEE table.  
4. Examine the EMPLOYEE table structure and data.  
5. Write the SQL SELECT query using WHERE, GROUP BY, HAVING, and ORDER BY clauses according to the practical steps.  
6. Execute the query and verify the output.  
7. Note down the results obtained.  
8. Save the work and take screenshots for record.

## Input / Output Details

### Input
- EMPLOYEE table containing columns: emp_id, emp_name, Department, Salary, joining_date.  
- SQL SELECT queries using WHERE, GROUP BY, HAVING, ORDER BY, and aggregate functions.

### Output
- Departments and their average salary for employees with salary > 20,000 and average salary > 30,000.  
- Output arranged in descending order of average salary.  
- Screenshots of query execution and results are attached in the repository.

## CREATING TABLE 
<img width="983" height="340" alt="Screenshot 2026-01-26 092959" src="https://github.com/user-attachments/assets/a345e9bc-a292-45ff-aebb-0302692883a5" />

### INSERT DATA
<img width="1095" height="395" alt="Screenshot 2026-01-26 093015" src="https://github.com/user-attachments/assets/01825ccd-8be4-4977-8dd1-f80f44900b47" />

### Average salary of employees for each department
<img width="1123" height="417" alt="Screenshot 2026-01-26 091912" src="https://github.com/user-attachments/assets/90abdcc8-349b-4213-b357-eeb55e8fb31a" />


### Consider only employees with salary > 20000
<img width="1120" height="426" alt="Screenshot 2026-01-26 091932" src="https://github.com/user-attachments/assets/daa7a000-d513-463a-83db-25d44a8cdfa2" />


### Departments where avg salary > 30000

<img width="1130" height="388" alt="Screenshot 2026-01-26 091951" src="https://github.com/user-attachments/assets/070cb18d-73c1-46e3-851c-cd940ca18d81" />


### Output: Final output in descending order of average salary
<img width="1127" height="438" alt="Screenshot 2026-01-26 092005" src="https://github.com/user-attachments/assets/06942367-cef4-40b7-96df-abe6245d2cf9" />



## Learning Outcome
After completing this experiment, the student will be able to:  
- Filter records using the WHERE clause.  
- Group records using GROUP BY.  
- Apply conditions on grouped data using HAVING.  
- Sort query results using ORDER BY.  
- Analyze data using aggregate functions for meaningful insights.
