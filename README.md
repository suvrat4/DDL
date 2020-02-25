# DDL(Data Defination Language):
Data Defination Language(DDL) ststements are used to define the database structure or schema. DDL statements create, modify and remove database object such as tables, indexes and users. Common DDL statements are 

* CREATE: To create object in the database.
* ALTER: Alters the structure of the database.
* DROP: Delete objects from the database.
* TRUNCATE: Remove all records from a table, including all spaces allocated for the records are removed.
* COMMENT: Add comment to the data dictionary
* RENAME: Rename an object.

### Usage of DDL:
The Data Defination Language(DDL) is used to create and destroy database and database objects. These sommand will primarily be used by database adminstartor during the setup and removal phase of a databse project.

### Create Table:
* CREATE TABLE command is used to create a new tabe. 'CREATE' is part of Data Defination Language(DDL).
* While creating a table we provide the basic information for each column together with their data type and sizes.

*Syntax:
CREATE TABLE <table name>
(
<column1 name>  <data type>
<column2 name>  <data type>
-----
-----
----
<columnn name>  <data type>
);


