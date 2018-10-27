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

