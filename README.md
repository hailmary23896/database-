# database-
Basic dml and ddl commands

Exercise I:  DDL Commands
1.	Create a table  employee with the following structure
  Column name	Constraint	Type of data
  Empno	Not null	Integer value
  Ename		Text
  Job		Text
  Mgr		Numeric value
  Hiredate		Date
  Sal		Float 
  Comm		Float
  Deptno	Not null	Numeric value

2.	Create a table department with the following structure
  Column name	Constraint	Type of data
  Deptno	Not null	Integer value
  Dname	Unique	Text
  Loc		Text

3.	Modify employee table to add a column called age with data type date.
4.	Modify employee table to add a column called grade with not null constraint.
5.	Add a check constraint to the employee table to verify that the grade is always s, 
  a or f.
6.	Modify employee table to change empno to a primary key constraint.
7.	Modify employee table by adding a referential integrity constraint (foreign key) on deptno to department table.
8.	Drop the column age from employee table.
9.	Modify the column width of dname of department table to 100.
10.	Drop the unique constraint on dname of department table.

dml


1.	Insert the following data into employee table
Empno	Ename	Job	Mgr	Hiredate	Sal	Comm	Deptno
7369	Smith	Clerk	7902	17-dec-80	800		20
7499	Allen	Salesman	7698	20-feb-81	1600	300	30
7521	Ward	Salesman	7698	22-feb-81	1250	500	30
7566	Jones	Manager	7839	02-apr-81	2975		20
7654	Martin	Salesman	7698	28-sep-81	1250	1400	30
7698	Blake	Manager	7839	01-may-81	2850		30
7782	Clark	Manager	7839	09-jun-81	2450		10
7788	Scott	Analyst	7566	09-dec-82	3000	200	20
7839	King	President		17-nov-81	5000		10
7844	Turner	Salesman	7698	08-sep-81	1500		30
7876	Adam	Clerk	7788	12-jan-83	1100		20
7900	James	Clerk	7698	03-dec-81	950		30
7902	Ford	Analyst	7566	03-dec-81	3000	200	20
7934	Miller	Clerk	7782	23-jan-82	1300		10

2.	Insert the following data into department  table
Deptno	Dname	Loc
10	Accounting	New York
20	Research	Dallas
30	Sales	Chicago
40	Operations	Boston

3.	Cancel the commission for all analysts.
4.	Modify the job title, salary and department number of Jones.
5.	List empno and name of all managers.
6.	List details of employees who belong to dept 10 or 30.
7.	List unique job titles.
8.	List employees whose name starts with ‘Sm’.
9.	List name, salary and P.F amount which is calculated as 10% of all employees. Display P.F as a separate column.
10.	List the name, job and start date of employees hired between February 20, 1981 and May 1, 1981. Order the query in ascending order of start date.
11.	List the maximum, average salary and number of employees in department 30.
12.	List the jobs and total salaries payable to each job title.
13.	Write SQL query to find the total number of clerks in the company.
14.	Write SQL query to find which department has exactly one employee as clerk.
15.	Write SQL query to find which department has the highest number of clerks? Show the deptno and count.
16.	Write SQL query to find the total number of employees in each department.
17.	List the lowest salary for different jobs used in a company and list them in descending order.
18.	Which department’s average salary is the lowest among all? Show the deptno, average salary.
19.	List the minimum, maximum and average salary for each job.
20.	List the names of the employees whose name contains ‘am’.
21.	Retrieve all the employees who are working in deptno=10 and who earn salary at least as much as any employee working in deptno=30.
22.	List the entire departments who have no employees.
23.	List all the employees who are working in the same department as their managers.
24.	List the names of all the employees with their name of the manager.
25.	How many different job titles exist in the employee table?

