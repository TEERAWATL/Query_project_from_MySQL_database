# Query_project_from_MySQL_database

#This README provides a summary of various SQL queries that can be executed on the classification_database and df1 tables, following the sequence provided. The classification_database table contains columns id, score, and symptom, while the df1 table contains columns id and user_type. These queries demonstrate how to perform data retrieval, filtering, aggregation, and various other operations on the table data.#

## Basic Queries

1. **Simple SELECT query**: Retrieve all records from a table.
2. **SELECT query with LIMIT**: Restrict the number of rows returned in the result.
3. **SELECT query with WHERE**: Filter the rows based on a specified condition.
4. **SELECT query with ORDER BY**: Sort the result based on a specified column.
5. **SELECT query with GROUP BY**: Group the result by one or more columns.
6. **SELECT query with HAVING**: Filter the result of a GROUP BY query based on a condition.
7. **SELECT query with multiple conditions using AND**: Return rows that satisfy all the conditions.
8. **SELECT query with multiple conditions using OR**: Return rows that satisfy at least one of the conditions.

## Join Queries

9. **SELECT query with INNER JOIN**: Combine rows from two or more tables based on a related column.
10. **SELECT query with LEFT JOIN**: Return all rows from the left table and the matched rows from the right table, filling with NULLs if no match is found.

## Advanced Queries

11. **SELECT query with subquery**: Use the result of another SELECT statement within the main query.
12. **SELECT query with score range**: Filter the rows based on a specified range of score.
13. **SELECT query with aggregate functions**: Perform calculations on a set of values and return a single value (e.g., COUNT, SUM, AVG, MIN, MAX).
14. **SELECT query with a combination of aggregate functions and GROUP BY**: Group the result and perform calculations on each group.
15. **SELECT query with aliases**: Assign temporary names to columns or tables in the query.
16. **SELECT query with a Common Table Expression (CTE)**: Define a temporary result set that can be referenced within the main query.
17. **SELECT query with a CASE statement**: Allow conditional logic in the query, returning different values based on conditions.
18. **SELECT query with COUNT and GROUP BY**: Group the rows and return the count for each group.
19. **SELECT query with COUNT, GROUP BY, and HAVING**: Group the rows, return the count for each group, and filter the groups based on a condition.
20. **SELECT query with SUM and GROUP BY**: Group the rows and calculate the sum of a specified column for each group.
21. **SELECT query with AVG and GROUP BY**: Group the rows and calculate the average of a specified column for each group.
