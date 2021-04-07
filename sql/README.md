# SQL Learning Path

## Day1:
* Table: CREATE TABLE, ALTER TABLE, ADD COLUMN, ALTER COLUMN, DROP TABLE
* Keys: PRIMANY KEY, FOREIGN KEY, UNIQUE KEY
* Constraints: NOT NULL, CHECK, DEFAULT
* INDEX
* Aggregate funtion
* SQL Practice Exercises: Create table as per requirement of below questions and try it your self

* How to create table with same structure with data?
* How to create table with same structure without data?
* How to display Last 10 records from Student table?
* How to fetch first 5 highest marks with Student table?
* How to display 1 to 100 numbers with using query?
* How to find the duplicate row count from specific table?
* How to delete duplicate rows from the table?
* How user can display following structure with using single SQL Query.
$
$$
$$$
* How to check for Email is correct or wrong with using single query?
* How to fetch maximum salary of Employee and minimum salary of Employee together from Employee table?
* List the Students whose name starts with P and surname starts with S?
* How to fetch last record from Student table?
* How to fetch all the Student who took admission at 2021?
* What is query to display odd records from Student table?
* What is query to display even records from Student table?
* How to find out manager name and employee name from same table?

 

## Day2:

* Conditional statements (CASE - WHEN - THEN - ELSE - END)
* JOIN: INNER JOIN, LEFT JOIN, FULL OUTER JOIN on one or multiple (in)equalities, CROSS JOIN, UNION and UNION ALL
* View: CREATE VIEW, ALTER VIEW, DELETE/DROP VIEW
* SQL Practice Exercises: Create table as per requirement of below questions and try it your self

 

Create Table with data:
salesman (salesman_id | name | city | commission)
customer (customer_id | cust_name | city | grade | salesman_id)
orders (ord_no | purch_amt | ord_date | customer_id | salesman_id)

 

* Write a SQL statement to prepare a list with salesman name, customer name and their cities for the salesmen and customer who belongs to the same city?
* Write a SQL statement to make a list with order no, purchase amount, customer name and their cities for those orders which order amount between 500 and 2000?
* Write a SQL statement to know which salesman are working for which customer?
* Write a SQL statement to find the list of customers who appointed a salesman for their jobs who gets a commission from the company is more than 12%?
* Write a SQL statement to find the list of customers who appointed a salesman for their jobs who does not live in the same city where their customer lives, and gets a commission is above 12% ?
* Write a SQL statement to find the details of a order i.e. order number, order date, amount of order, which customer gives the order and which salesman works for that customer and how much commission he gets for an order?
* Write a SQL statement to make a join on the tables salesman, customer and orders in such a form that the same column of each table will appear once and only the relational rows will come?
* Write a SQL statement to make a list in ascending order for the customer who works either through a salesman or by own?
* Write a SQL statement to make a list in ascending order for the customer who holds a grade less than 300 and works either through a salesman or by own?
* Write a SQL statement to make a report with customer name, city, order number, order date, and order amount in ascending order according to the order date to find that either any of the existing customers have placed no order or placed one or more orders?
* Write a SQL statement to make a report with customer name, city, order number, order date, order amount salesman name and commission to find that either any of the existing customers have placed no order or placed one or more orders by their salesman or by own?
* Write a SQL statement to make a list in ascending order for the salesmen who works either for one or more customer or not yet join under any of the customers?
* Write a SQL statement to make a list for the salesmen who works either for one or more customer or not yet join under any of the customers who placed either one or more or*ders or no order to their supplier?
* Write a SQL statement to make a list for the salesmen who either work for one or more customers or yet to join any of the customer. The customer may have placed, either one or more orders on or above order amount 2000 and must have a grade, or he may not have placed any order to the associated supplier?
* Write a SQL statement to make a report with customer name, city, order no. order date, purchase amount for those customers from the existing list who placed one or more orders or which order(s) have been placed by the customer who is not on the list?
* Write a SQL statement to make a report with customer name, city, order no. order date, purchase amount for only those customers on the list who must have a grade and placed one or more orders or which order(s) have been placed by the customer who is neither in the list not have a grade?
* Write a SQL statement to make a cartesian product between salesman and customer i.e. each salesman will appear for all customer and vice versa?
* Write a SQL statement to make a cartesian product between salesman and customer i.e. each salesman will appear for all customer and vice versa for that salesman who belongs to a city?
* Write a SQL statement to make a cartesian product between salesman and customer i.e. each salesman will appear for all customer and vice versa for those salesmen who belongs to a city and the customers who must have a grade?
* Write a query in SQL to display all the data of employees including their department?

## Day3:
* Function
* Store Procedure
* Cursor
