Some of The Most Important SQL Commands
- `SELECT`: extracts data from a database
    - `SELECT DISTINCT`: used to return only different values
    - `COUNT`: ...
- `WHERE`: used to extract only those records that fulfill a specified condition.
	- Operators: `=`, `<`, `>`, `<=`, `>=`, `<>` (not equal), `BETWEEN`, `LIKE`, `IN`
    - `LIKE`: used in a WHERE clause to search for a specified pattern in a column
        - The simble `%` rappresents zero, one or multiple characters
        - The simble `_` rapresents one single character
        - For a better comprehension see the examples of the [w3school documentation](https://www.w3schools.com/sql/sql_like.asp) (very clarifying)
- `AND`, `OR`, `NOT` operators
- `ORDER BY`: used to sort the result-set in ascending or descending order
    - `ASC|DESC`: To select the sorting order (ascending o descending)
- `INSERT INTO`: inserts new data into a database
	- `VALUE`: ...
- `IS NULL | IS NOT NULL`: commands to check if a field is `NULL` or not
- `UPDATE`: used to modify the existing records in a table
    - About `WHERE` clause: If u omit the `WHERE` clause in an `UPDATE`, all recorda in the talbe will be updated
- `DELETE`: used to delete existing records in a table
	- About `WHERE` clause: same of `UPDATE`
- `SELECT TOP`: used to specify the number of records to return
    - `SELECT TOP n FROM ...;`
	- `SELECT * FROM ...`
	  `LIMIT n;`
	- `SELECT * FROM ..`
	  `FETCH FIRST n ROWS ONLY;`
	- `SELECT TOP n PERCENT * FROM ...;     -- Select half of them`
	- About `WHERE` clause: same of `UPDATE`

- `MIN(col)` and `MAX(col)` functions: used to return the smallest or largest value of the selecter column
	- `AS`: Example: `SELECT MIN(col) AS col-1` or `SELECT col AS alias_name`
- `COUNT()`: returns the number of rows that matches a specified criterion.
- `AVG()`: returns the average value of a numeric column
- `SUM()`: returns the total sum of a numeric column
- Wildcard Characters: A widcard character is used to substitute one or moore character in a string. See the [w3school documentatio](https://www.w3schools.com/sql/sql_wildcards.asp)
- `IN`: Allows you to specify multiple values in a `WHERE` clause and is a shorthand for multpiple `OR` conditions. Example:
    ```
    SELECT column_name(s)
    FROM table_name
    WHERE column_name IN (SELECT statement)
    ```
- `BETWEEN`: Selects values (numbers, text or dates) within a given range and it also includes extremes.
- `JOIN` clause is used to combine rows from tables, based on a relater column between them.
    - [Types of `JOIN`s](https://www.geeksforgeeks.org/sql-join-set-1-inner-left-right-and-full-joins/): `INNER JOIN` (intersection), `LEFT JOIN`, `RIGHT JOIN`, `FULL JOIN` (union)
- `UNION`:  Eveused to combine the result-set of two or more `SELECT` statements. It selects only distinct valuest by default. To allow duplicate values, use `UNION ALL`.
- `GROUP BY`: The `GROUP BY` statement groups rows that have the same values into summary rows.






- CREATE DATABASE: creates a new database
- ALTER DATABASE: modifies a database
- CREATE TABLE: creates a new table
- ALTER TABLE: modifies a table
- DROP TABLE: deletes a table
- CREATE INDEX: creates an index (search key)
- DROP INDEX: deletes an index
 
- SET ????
