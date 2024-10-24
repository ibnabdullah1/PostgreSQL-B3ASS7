# Questions (Answer 10 Questions):

1. **What is PostgreSQL?**

   PostgreSQL is an open-source, object-relational database management system (DBMS) known for its robustness, scalability, and support for advanced data types and complex queries. It uses SQL for database management and includes procedural languages such as full-text search, custom data types, and PL / pgSQL.

2. **What is the purpose of a database schema in PostgreSQL?**

   In PostgreSQL, a schema is a logical collection that contains various database objects, including tables, views, indexes, and functions. Schema helps to organize and manage these objects within the database. It creates a separate namespace that allows multiple objects with the same name to be used separately.

3. **Explain the primary key and foreign key concepts in PostgreSQL.**

   The primary key is one or more columns in a table that uniquely identify each record. A foreign key is a column or group of columns that corresponds to a primary key in another table, and is used to create relationships between tables.

4. **What is the difference between the VARCHAR and CHAR data types?**

   VARCHAR is a variable length data type, where you can set the maximum length and it does not save extra space. On the other hand, CHAR is a fixed-length data type, which stores exactly the specified length of data and fills the rest of the space with blanks.

5. **Explain the purpose of the WHERE clause in a SELECT statement.**

   Using the WHERE clause, you can filter the data by specifying certain conditions in the SELECT statement. It only returns records that meet the conditions.

6. **What are the LIMIT and OFFSET clauses used for?**

   Using the LIMIT clause you can limit a certain number of records and with the OFFSET clause you can exclude a certain number of records from the beginning of the data set.

7. **How can you perform data modification using UPDATE statements?**

   With the UPDATE statement, you can update the data of a particular record in the table. Typically, by selecting specific records through the WHERE clause, you change the data in those records.

8. **What is the significance of the JOIN operation, and how does it work in PostgreSQL?**

   Using the JOIN operation, you can add the data of multiple tables together. It collects data by creating relationships between tables, such as: INNER JOIN, LEFT JOIN, RIGHT JOIN, etc.

9. **Explain the GROUP BY clause and its role in aggregation operations.**

   Using the GROUP BY clause, you can group similar data and apply aggregate functions such as COUNT, SUM, AVG on them. It summarizes multiple records into a single record, based on specific criteria.

10. **How can you calculate aggregate functions like COUNT, SUM, and AVG in PostgreSQL?**

    Using the aggregate functions, you can define different amounts of data.

- Count the number of records using `COUNT ()`.
- Using `SUM ()` to determine the sum of all the values of a particular column.
- The average value of the column is determined using `AVG ()`.
