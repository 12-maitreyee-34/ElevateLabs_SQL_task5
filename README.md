This repository illustrates the design and querying of a basic Customer Order Management System with MySQL Workbench. It covers database design, table creation, inserting data, and applying different types of SQL joins to investigate relationships between customers and orders.


INNER JOIN: Retrieves customers who have made at least one order.


RIGHT JOIN: Retrieves all orders, including those without a corresponding customer (if any).


LEFT JOIN: Shows all customers, including those who have not placed an order.


FULL OUTER JOIN (UNION): Joining left and right joins to display all customers and all orders.


CROSS JOIN: Combines every customer with every order (cartesian join).


SELF JOIN: Compares addresses to identify customers from the same city.


NATURAL JOIN: Automatically joins both tables on the common customer_id column.


INNER JOIN with WHERE: Filters and shows customers whose order amount is over ₹200.

