# Data-Source
## Database Documentation
This database is made to manage the data for employees. This database is consisting of 6 tables or entities which are employees, department employees, department, department manager, titles, and salaries.
## Entity Relationship Diagram (ERD)
This are the representation of the connection between the 6 entities
![ERD](https://github.com/mrcz8/Data-Source/blob/main/ERD.png)
## Entity Names and description
Employees – is responsible for storing the data of all employees and the hired date.

Department employees – storing the record of employees and the department where they are assigned.

Departments – responsible for storing the department names.

Department manager – storing the data of a manager.

Titles – responsible for the position of the employees.

Salaries – records of salaries of employees.

## QUERIES
### Aggregate Function
###  Aggregate Function (AVG)
  is an aggregate function that returns the average value for a numeric column. This can help to total the average of a employee.
  ![Aggregate function (AVG)](https://github.com/mrcz8/Data-Source/blob/main/Aggregate%20function%20(AVG).png)
### Aggregate Function (COUNT) 
  is a function that takes the name of a column as a column as an argument and counts the number of rows where the column is not NULL.
  ![Aggregate function (COUNT)](https://github.com/mrcz8/Data-Source/blob/main/Aggregate%20function%20(COUNT).png)
### Aggregate Function (MAX)
  is a function that takes the name of a column as an argument and returns the largest value in that column. Through this query we can fetch the maximum value of a data.
  ![Aggregate function (MAX)](https://github.com/mrcz8/Data-Source/blob/main/Aggregate%20function%20(MAX).png)
### Aggregate Function (MIN) 
  is a function that takes the name of a column as an argument and returns the smallest value in that column. Through this query we can fetch the minimum value of a data.
  ![Aggregate function (MIN)](https://github.com/mrcz8/Data-Source/blob/main/Aggregate%20function%20(Min).png)
### Aggregate Function (SUM)
  is a function that takes the name of a column as an argument and returns the sum value in that column.
  ![Aggregate function (SUM)](https://github.com/mrcz8/Data-Source/blob/main/Aggregate%20function%20(SUM).png)
  
### ALIAS 
	This query allows you to rename a column or table using alias. You can rename a column or table temporarily by giving another name.
  ![Alias](https://github.com/mrcz8/Data-Source/blob/main/Alias.png)
### BETWEEN
	This query allows you to easily test or select values within a given range. The values can be text, numbers or other data that you put in the entities.
  ![Between](https://github.com/mrcz8/Data-Source/blob/main/Between.png)
### CASE STATEMENT
	This query helps you to return a value with a specified condition, we can use condition like WHERE, ORDER BY and GROUP BY.
  ![Case Statement](https://github.com/mrcz8/Data-Source/blob/main/Case%20Statement.png)
### COALESC
  This query used to handle NULL values. During the expression evaluation process the NULL values are replaced with the user-defined value.
  ![COALESC](https://github.com/mrcz8/Data-Source/blob/main/COALESC.png)
### DELETING MULTIPLE ROWS
  ![Delete Multiple rows1](https://github.com/mrcz8/Data-Source/blob/main/Delete%20Multiple%20rows1.png)
  ![Delete Multiple rows2](https://github.com/mrcz8/Data-Source/blob/main/Delete%20Multiple%20rows2.png)
### EXISTS
  This query is used in combination with a subquery and is considered to be met, if the subquery returns at least one row.
  ![Exists](https://github.com/mrcz8/Data-Source/blob/main/Exists.png)
### GROUP BY
  This query allows you to collapse a field into its distinct values.
  ![Group By](https://github.com/mrcz8/Data-Source/blob/main/Group%20By.png)
### IS NULL AND NOT NULL
  is Null and NOT NULL are operators used with the where clause to test for empty values.
  ![IS NULL AND NOT NULL](https://github.com/mrcz8/Data-Source/blob/main/IS%20NULL%20AND%20NOT%20NULL.png)

### JOIN QUERIES
  By using a join you can executes faster. The retrieval time of the query using joins is faster than a subquery. By using joins, you can maximize the calculation burden on the database, instead of multiple queries using one join query.
### INNER JOIN
  This query
  ![Inner Join](https://github.com/mrcz8/Data-Source/blob/main/Inner%20Join.png)
### LEFT JOIN
  ![LEFT JOIN](https://github.com/mrcz8/Data-Source/blob/main/LEFT%20JOIN.png)
### RIGHT JOIN
  ![RIGHT JOIN](https://github.com/mrcz8/Data-Source/blob/main/RIGHT%20JOIN.png)
  
### LIMIT
  This query is used to retrieve records from one or more tables in a database and limit the number of records returned based on a limit value.
  ![Limit](https://github.com/mrcz8/Data-Source/blob/main/Limit.png)
### ORDER BY
  This query is to fetch all the records from the dept_emp table order by emp_no in descending order and dept_no in the ascending order.
  ![order by](https://github.com/mrcz8/Data-Source/blob/main/order%20by.png)
### HAVING
  this query is to fetch or retrieve departments who has less than 5 employees working on it.
  ![having](https://github.com/mrcz8/Data-Source/blob/main/having.png)
### SELECT
  This query fetches all data (all column and row)of table. but this example i use a condition.
  ![image](https://github.com/mrcz8/Data-Source/blob/main/image.png)
