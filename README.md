# SQL-Important-Questions-and-Concepts
This repository is the collection of important SQL questions and concepts.

# Cracking the SQL Interview


## A comprehensive guide before your next interview

1. SQL was developed as an integral part of

SQL - Structured Query Language is a domain-specific language used in programming and designed for managing data held in a relational database management system (RDBMS), or for stream processing in a relational data stream management system (RDSMS).

Although SQL is an ANSI (American National Standards Institute) standard, there are different versions of the SQL language.

However, to be compliant with the ANSI standard, they all support at least the major commands (such as SELECT, UPDATE, DELETE, INSERT, WHERE) in a similar manner.

Note: Most of the SQL database programs also have their own proprietary extensions in addition to the SQL standard!

What Can SQL do?

SQL can execute queries against a database
SQL can retrieve data from a database
SQL can insert records in a database
SQL can update records in a database
SQL can delete records from a database
SQL can create new databases
SQL can create new tables in a database
SQL can create stored procedures in a database
SQL can create views in a database
SQL can set permissions on tables, procedures, and views

2. What does SQL stand for?

SQL stands for Structured Query Language. SQL lets you access and manipulate databases. SQL is an ANSI (American National Standards Institute) standard.

3. SQL is (referring to it as a Programming Language)

SQL is a declarative language in which the expected result or operation is given without the specific details about how to accomplish the task. The steps required to execute SQL statements are handled transparently by the SQL database. Sometimes SQL is characterized as non-procedural because procedural languages generally require the details of the operations to be specified, such as opening and closing tables, loading and searching indexes, or flushing buffers and writing data to filesystems. Therefore, SQL is considered to be designed at a higher conceptual level of operation than procedural languages because the lower level logical and physical operations aren't specified and are determined by the SQL engine or server process that executes it.

4. Which of the following is NOT a SQL command? (SELECT, REMOVE, UPDATE, INSERT)

REMOVE is not a valid SQL command.

Some of The Most Important SQL Commands

SELECT - extracts data from a database


UPDATE - updates data in a database


DELETE - deletes data from a database


INSERT INTO - inserts new data into a database


CREATE DATABASE - creates a new database


ALTER DATABASE - modifies a database


CREATE TABLE - creates a new table


ALTER TABLE - modifies a table


DROP TABLE - deletes a table


CREATE INDEX - creates an index (search key)


DROP INDEX - deletes an index


5. What is MySQL?

MySQL is the most popular Open Source SQL database management system developed, distributed, and supported by Oracle Corporation.

Another common SQL interview question regarding MySQL may come in a different form

“What is the difference between SQL and MySQL?” or Difference between SQL and MySQL:

SQL is a structured query language that is used for manipulating and accessing the relational database, on the other hand, MySQL itself is a relational database that uses SQL as the standard database language.

6. What are some properties of PL/SQL?

PL/SQL is a combination of SQL along with the procedural features of programming languages. It was developed by Oracle Corporation in the early 90's to enhance the capabilities of SQL. PL/SQL is one of three key programming languages embedded in the Oracle Database, along with SQL itself and Java.

Another common SQL interview question regarding PL/SQL may come in a different form:

“What is the difference between SQL and PL/SQL? or Difference between SQL and PL/SQL:

SQL is a Structured Query Language used to issue a single query or execute a single insert/update/delete.

PL-SQL is a programming language SQL, used to write full programs using variables, loops,operators etc. to carry out multiple selects/inserts/updates/deletes.

SQL may be considered as the source of data for our reports, web pages and screens.

PL/SQL can be considered as the application language similar to Java or PHP. It might be the language used to build, format and display those reports, web pages and screens.

SQL is a data oriented language used to select and manipulate sets of data.

PL/SQL is a procedural language used to create applications.

SQL vs. PL-SQL

SQL is used to write queries, DDL and DML statements.
PL/SQL is used to write program blocks, functions, procedures triggers,and packages.
SQL is executed one statement at a time.
PL/SQL is executed as a block of code.
SQL is declarative, i.e., it tells the database what to do but not how to do it. Whereas, PL/SQL is procedural, i.e., it tells the database how to do things.
SQL can be embedded within a PL/SQL program. But PL/SQL cant be embedded within a SQL statement.
7. What are the possible values for the BOOLEAN data field in MySQL?

MySQL uses TINYINT(1) data type to represent boolean values. A value of zero is considered false . Non-zero values are considered true .

8. What data type would you choose if you wanted to store the distance (rounded to the nearest mile)?

INTEGER (or INT )   
9. Which are valid SQL keywords (statements & clauses)

SELECT - extracts data from a database


FROM - clause is used to specify the tables to extract data from


WHERE - clause is used to extract only those records that fulfill a specified condition.


GROUP BY - is often used with aggregate functions (COUNT , MAX , MIN , SUM , AVG ) to group the result-set by one or more columns.


HAVING - clause was added to SQL because the WHERE keyword could not be used with aggregate functions.


ORDER BY - keyword is used to sort the result-set in ascending or descending order.


UPDATE - updates data in a database

DELETE - deletes data from a database


INSERT INTO - inserts new data into a database


CREATE DATABASE - creates a new database

ALTER DATABASE - modifies a database


CREATE TABLE - creates a new table


ALTER TABLE - modifies a table

DROP TABLE - deletes a table


CREATE INDEX - creates an index (search key)


DROP INDEX - deletes an index


**10. Which of the following are valid SQL comments?**

Comments are used to explain sections of SQL statements, or to prevent execution of SQL statements.

Single line comments start with -- .

Any text between -- and the end of the line will be ignored (will not be executed).

The following example uses a single-line comment as an explanation:

--Select all:


SELECT * FROM Customers;


Multi-line comments start with /* and end with */ .

Any text between /* and */ will be ignored.

The following example uses a multi-line comment as an explanation:


/*Select all the columns


of all the records


in the Customers table:*/


SELECT * FROM Customers;


The following example uses a multi-line comment to ignore many statements:

/*SELECT * FROM Customers;


SELECT * FROM Products;*/


SELECT * FROM Suppliers;

11. Which SQL statement is used to extract data from a database?


A SELECT statement retrieves zero or more rows from one or more database tables or database views.

As SQL is a declarative programming language, SELECT queries specify a result set, but do not specify how to calculate it.

The SELECT statement has many optional clauses:

WHERE specifies which rows to retrieve.

GROUP BY groups rows sharing a property so that an aggregate function can be applied to each group.

HAVING selects among the groups defined by the GROUP BY clause.

ORDER BY specifies an order in which to return the rows.

AS provides an alias which can be used to temporarily rename tables or columns.

12. How to select all records from the table 'Products'?

SELECT * FROM Products;

If you want to select all the fields available in the table, use the * syntax as this:

SELECT * FROM Products;

13. Can we rename a column in the output of SQL query?

Yes, using AS .

SQL aliases are used to give a column in a table, a temporary name.

Aliases are often used to make column names more readable.

An alias only exists for the duration of the query.

Alias Column Syntax:

SELECT column_name AS alias_name
FROM table_name;

14. With SQL, how do you select a column named "FirstName" from a table named "Customers"?

SELECT FirstName FROM Customers;

The SELECT statement is used to select data from a database.

The data returned is stored in a result table, called the result-set.

SELECT Syntax

SELECT column1, column2, ...


FROM table_name;
Here, column1, column2, ... are the field names of the table you want to select data from. If you want to select all the fields available in the table, use the following syntax:

SELECT * FROM table_name;


15. What does the SQL FROM clause do?

The SQL FROM clause is used to list the tables and any joins required for the SQL statement.

16. Which SQL statement is used to return only different values?

The SELECT DISTINCT statement is used to return only distinct (different) values.

Inside a table, a column often contains many duplicate values; and sometimes you only want to list the different (distinct) values.

SELECT DISTINCT Syntax

SELECT DISTINCT column1, column2, ...
FROM table_name;

17. Consider the following schema ADDRESSES (id, street_name, number, city, state) Which of the following query would display the distinct cities in the ADDRESSES table?

SELECT DISTINCT city FROM addresses;

(same theory applies as for the previous question)

18. With SQL, how do you select all the records from a table named "Customers" where the value of the column "FirstName" is "John"?

SELECT * FROM Customers WHERE FirstName='John';

The WHERE clause is used to filter records.

The WHERE clause is used to extract only those records that fulfill a specified condition.

SQL requires single quotes around text values (most database systems will also allow double quotes).

19. The OR operator displays a record if ANY conditions listed are true. The AND operator displays a record if ALL of the conditions listed are true.

The WHERE clause can be combined with AND , OR , and NOT operators.

The AND and OR operators are used to filter records based on more than one condition:

The AND operator displays a record if all the conditions separated by AND are TRUE .

The OR operator displays a record if any of the conditions separated by OR are TRUE .

The NOT operator displays a record if the condition(s) is NOT TRUE .

AND Syntax

SELECT column1, column2, ...
FROM table_name
WHERE condition1 AND condition2 AND condition3 …;


OR Syntax

SELECT column1, column2, ...
FROM table_name
WHERE condition1 OR condition2 OR condition3 ...;


NOT Syntax

SELECT column1, column2, ...
FROM table_name
WHERE NOT condition;


20. Which of the following SQL statements has correct syntax?

SELECT * FROM Table1 WHERE Column1 >= 100

SQL Comparison Operators

'=' Equal to

'>' Greater than

'<' Less than

'>=' Greater than or equal to

'<=' Less than or equal to

'≠' Not equal to

21. With SQL, how do you select all the records from a table named "Customers" where the "FirstName" is "John" and the "LastName" is "Jackson"?

SELECT * FROM Customers WHERE FirstName='John' AND LastName='Jackson'
Same answers as for the previous 2 questions.

You must use the AND operator that displays a record if all the conditions separated by AND are TRUE and the = (‘equal’) comparison operator.


22. How to select random 10 rows from a table?

The easiest way to generate random rows in MySQL is to use the ORDER BY RAND() clause.

SELECT * FROM tbl ORDER BY RAND() LIMIT 10;
This can work fine for small tables. However, for big table, it will have a serious performance problem as in order to generate the list of random rows, MySQL need to assign random number to each row and then sort them.

Even if you want only 10 random rows from a set of 100k rows, MySQL need to sort all the 100k rows and then, extract only 10 of them.


23. Examine the following code. What will the value of price be if the statement finds a NULL value? SELECT name, ISNULL(price, 50) FROM PRODUCTS

What is a NULL Value?

A field with a NULL value is a field with no value.

If a field in a table is optional, it is possible to insert a new record or update a record without adding a value to this field. Then, the field will be saved with a NULL value.

Note: It is very important to understand that a NULL value is different from a zero value or a field that contains spaces. A field with a NULL value is one that has been left blank during record creation!

How can you return a default value for a NULL?

MySQL

The MySQL IFNULL() function lets you return an alternative value if an expression is NULL:

SELECT ProductName, UnitPrice * (UnitsInStock + IFNULL(UnitsOnOrder, 0))
FROM Products
or we can use the COALESCE() function, like this:

SELECT ProductName, UnitPrice * (UnitsInStock + COALESCE(UnitsOnOrder, 0))
FROM Products
SQL Server

The SQL Server ISNULL() function lets you return an alternative value when an expression is NULL :

SELECT ProductName, UnitPrice * (UnitsInStock + ISNULL(UnitsOnOrder, 0))
FROM Products


MS Access

The MS Access IsNull() function returns TRUE (-1) if the expression is a null value, otherwise FALSE (0) :

SELECT ProductName, UnitPrice * (UnitsInStock + IIF(IsNull(UnitsOnOrder), 0, UnitsOnOrder))
FROM Products
Oracle

The Oracle NVL() function achieves the same result:

SELECT ProductName, UnitPrice * (UnitsInStock + NVL(UnitsOnOrder, 0))
FROM Products
24. Which operator is used to search for a specified text pattern in a column?

The LIKE operator is used in a WHERE clause to search for a specified pattern in a column.

There are two wildcards used in conjunction with the LIKE operator:

% - The percent sign represents zero, one, or multiple characters

_ - The underscore represents a single character


Examples:

WHERE CustomerName LIKE 'a%' -- Finds any values that starts with "a"


WHERE CustomerName LIKE '%a' -- Finds any values that ends with "a"


WHERE CustomerName LIKE '%or%' -- Finds any values that have "or" in any position


WHERE CustomerName LIKE '_r%' -- Finds any values that have "r" in the second position


WHERE CustomerName LIKE 'a_%_%' -- Finds any values that starts with "a" and are at least 3 characters in length


WHERE ContactName LIKE 'a%o' -- Finds any values that starts with "a" and ends with "o"


25. How to write a query to show the details of a student from Students table whose FirstName starts with 'K'?

SELECT * FROM Students WHERE FirstName LIKE 'K%'.

Explanation from previous question applies.

26. Which operator is used to select values within a range?

The BETWEEN operator selects values within a given range. The values can be numbers, text, or dates.

The BETWEEN operator is inclusive: begin and end values are included.

BETWEEN Syntax

SELECT column_name(s)
FROM table_name
WHERE column_name BETWEEN value1 AND value2;

27. Which of the following SQL statements is correct?

SELECT * FROM Sales WHERE Date BETWEEN '01/12/2017' AND '01/01/2018'

Explanation from previous question applies.

28. With SQL, how do you select all the records from a table named "Customers" where the "LastName" is alphabetically between (and including) "Brooks" and "Gray"?

SELECT * FROM Customers WHERE LastName BETWEEN 'Brooks' AND 'Gray'  
Explanation from previous question applies.


29. The 'IN' SQL keyword…

The IN operator allows you to specify multiple values in a WHERE clause.

The IN operator is a shorthand for multiple OR conditions.

IN Syntax

SELECT column_name(s)
FROM table_name
WHERE column_name IN (value1, value2, ...);


or:



SELECT column_name(s)
FROM table_name
WHERE column_name IN (SELECT STATEMENT); --subquery
