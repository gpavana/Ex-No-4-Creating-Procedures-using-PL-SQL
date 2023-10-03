# Ex. No: 4 Creating Procedures using PL/SQL

### AIM: To create a procedure using PL/SQL.

### Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table

### Program:
```
SQL> create or replace procedure insert_employee_data AS
  2  BEGIN
  3  INSERT INTO employee(empid, empname, dept, salary)
  4  VALUES(1,'John','HR',50000);
  5  INSERT INTO employee(empid, empname, dept, salary)
  6  VALUES(2,'Joe','IT',60000);
  7  INSERT INTO employee(empid, empname, dept, salary)
  8  VALUES(3,'Bob','Finance',55000);
  9  end;
 10  /
```

### Output:
![image](https://github.com/gpavana/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/118787343/129bec12-1079-4eee-b98a-8789c6441ccc)

### Result:
Therefore,procedure using PL/SQL created successfully.
