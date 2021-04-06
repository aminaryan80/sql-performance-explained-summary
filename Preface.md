# Developers Need to Index

SQL main benefit is the capability to separate “what” and “how”. An SQL statement is a straight description what is needed without instructions as to how to get it done. Consider the following example:
```SQL
SELECT date_of_birth
FROM employees
WHERE last_name = 'WINAND'
```
The SQL query reads like an English sentence that explains the requested data. Writing SQL statements generally does not require any knowledge about inner workings of the database or the storage system.

The separation of concerns — what is needed versus how to get it — works remarkably well in SQL, but it is still not perfect. the author must know a little bit about the database to prevent performance problems.

the author must know a little bit about the database to prevent performance problems.

