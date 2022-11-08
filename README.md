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

### DATABASE
> Database is a collection of interrelated data which helps in the efficient retrieval, insertion, and deletion of data from the database and organizes the data in the form of tables, views, schemas, reports, etc. For Example, a university database organizes the data about students, faculty, admin staff, etc. which helps in the efficient retrieval, insertion, and deletion of data from it.


### Database Management System
> The software which is used to manage databases is called Database Management System (DBMS). For Example, MySQL, Oracle, etc. are popular commercial DBMS used in different applications.

> Database Management System or DBMS in short refers to the technology of storing and retrieving users data with utmost efficiency along with appropriate security measures.
 
#### DBMS allows users the following tasks: 
- Data Definition: It helps in the creation, modification, and removal of definitions that define the organization of data in the database. 
- Data Updation: It helps in the insertion, modification, and deletion of the actual data in the database. 
- Data Retrieval: It helps in the retrieval of data from the database which can be used by applications for various purposes. 
- User Administration: It helps in registering and monitoring users, enforcing data security, monitoring performance, maintaining data integrity, dealing with concurrency control, and recovering information corrupted by unexpected failure.

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

- [wild-cards](https://popsql.com/queries/-NGBYeSLv6nDV4PxpwUY/wild-cards?access_token=aaedcac27c9633da4b635537d1f9cf7e)

- [join](https://popsql.com/queries/-NGBsHlSTy-mdOe0-2am/join?access_token=676c6e69cab515b65759f4e106e9d766)

- [union](https://popsql.com/queries/-NGBfB9WY6B2nKWfUnzY/union?access_token=0e14c9f8fa7c24be14ab6865242709e6)

- [create-databases(new)](https://popsql.com/queries/-NGFMcQFaCUO9NMsORNd/create-databasesnew?access_token=5b268729bc2554a40d5bbd8b0637b476)

- [create-db-hr](https://popsql.com/queries/-NGFPr1l-KObbcq7RJyl/create-db-hr?access_token=746746773a2b9b48dbe45e754196e75b)

- [create-db-invoicing](https://popsql.com/queries/-NGFQVlnwPiCyIit-NmV/create-db-invoicing?access_token=451b2635beace063f69d86a6e2ce7908)

- [create-db-store](https://popsql.com/queries/-NGFQqmrztmPudgonv8c/create-db-store?access_token=922581bfc433a871946881f0eefa2f9d)

- [create-db-inventory](https://popsql.com/queries/-NGFQuh9WA4pvpcp7aRf/create-db-inventory?access_token=a216f44a46dcd8b8eb6c2cd4db5e1967)

- [nested-queries](https://popsql.com/queries/-NGFYECFxER9Ofn6LHsj/nested-queries?access_token=c39407efc608bdfc0874c8a885426ff1)

- [on-delete](https://popsql.com/queries/-NGFmhBEHegCYp7ExM7i/on-delete?access_token=a687481155731d7afe9645b33862f68e)

- [triggers](https://popsql.com/queries/-NGFrqI2kOsckr8G21v6/triggers?access_token=82a85c527f330e026935529ff673d09d)


