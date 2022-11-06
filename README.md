# SQL
## SQL is a standard language for accessing and manipulating databases.

 ### What is SQL? <br>
- SQL stands for Structured Query Language
- SQL lets you access and manipulate databases
- SQL became a standard of the American National Standards Institute (ANSI) in 1986, and of the International Organization for Standardization (ISO) in 1987
### What Can SQL do?
- SQL can execute queries against a database
- SQL can retrieve data from a database
- SQL can insert records in a database
- SQL can update records in a database
- SQL can delete records from a database
- SQL can create new databases
- SQL can create new tables in a database
- SQL can create stored procedures in a database
- SQL can create views in a database
- SQL can set permissions on tables, procedures, and views
- 
### SQL is a Standard - BUT....
Although SQL is an ANSI/ISO standard, there are different versions of the SQL language.

However, to be compliant with the ANSI standard, they all support at least the major commands (such as ```SELECT```, ```UPDATE```, ```DELETE```, ```INSERT```, ```WHERE```) in a similar manner.

#### Note: Most of the SQL database programs also have their own proprietary extensions in addition to the SQL standard!

### Using SQL in Your Web Site
To build a web site that shows data from a database, you will need:
- An RDBMS database program (i.e. MS Access, SQL Server, MySQL)
- To use a server-side scripting language, like PHP or ASP
- To use SQL to get the data you want
- To use HTML / CSS to style the page

### RDBMS
> RDBMS stands for Relational Database Management System. <br>
RDBMS is the basis for SQL, and for all modern database systems such as MS SQL Server, IBM DB2, Oracle, MySQL, and Microsoft Access. <br>
The data in RDBMS is stored in database objects called tables. A table is a collection of related data entries and it consists of columns and rows. <br>

Look at the "Customers" table:

Example <br>
```SELECT * FROM Customers;```

Every table is broken up into smaller entities called fields. A field is a column in a table that is designed to maintain specific information about every record in the table.

A record, also called a row, is each individual entry that exists in a table. For example, there are 91 records in the above Customers table. A record is a horizontal entity in a table.

A column is a vertical entity in a table that contains all information associated with a specific field in a table.

### Database Tables
A database most often contains one or more tables. Each table is identified by a name (e.g. "Customers" or "Orders"). Tables contain records (rows) with data.

### SQL Statements
Most of the actions you need to perform on a database are done with SQL statements.

The following SQL statement selects all the records in the "Customers" table:

Example <br>
```SELECT * FROM Customers;```

### Keep in Mind That...
- SQL keywords are NOT case sensitive: ```select``` is the same as ```SELECT```


### Semicolon after SQL Statements?
Some database systems require a semicolon at the end of each SQL statement.

Semicolon is the standard way to separate each SQL statement in database systems that allow more than one SQL statement to be executed in the same call to the server.

### Some of The Most Important SQL Commands
```SELECT``` - extracts data from a database <br>
```UPDATE``` - updates data in a database<br>
```DELETE``` - deletes data from a database<br>
```INSERT INTO``` - inserts new data into a database<br>
```CREATE DATABASE``` - creates a new database<br>
```ALTER DATABASE``` - modifies a database<br>
```CREATE TABLE``` - creates a new table<br>
```ALTER TABLE``` - modifies a table<br>
```DROP TABLE``` - deletes a table<br>
```CREATE INDEX``` - creates an index (search key)<br>
```DROP INDEX``` - deletes an index<br>


















# SQL Queries

- [functions-in-sql](https://popsql.com/queries/-NG6w-Xd4KtIm1PtAehi/functions-in-sql?access_token=0f5bea89833be8c16d9d3f95207e8f5a)

- [company-database](https://popsql.com/queries/-NG6cmIf5-q78X1ZYOD5/company-database?access_token=9ab971e34b52785a38c79d0c4896dc91)

- [test-table](https://popsql.com/queries/-NG2EP6NcQh7P-zHbRkD/test-table?access_token=39c4587e71d4729a398658e29bdea3df)

- [data-types-in-sql](https://popsql.com/queries/-NG50BV7ZFsJg8zxMcFB/data-types-in-sql?access_token=f0ef13361fe61fffc997b61edff405da)

- [update-and-delete-in-table](https://popsql.com/queries/-NG5IAAy5guhK0fwvoIV/update-and-delete-in-table?access_token=2063ebd5ea175c99c7c32e72701c0f17)

- [basic-queries](https://popsql.com/queries/-NG5QMznetiuCUcyj9v4/basic-queriessql?run_id=24490880)

- [sample-queries](https://popsql.com/queries/-NG28GVLBu1rBKhqdbGI/sample-queries?run_id=24490967)
