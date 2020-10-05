# The Ultimate SQL Course

## Databases
A structured set of computerized data with accessible interface
1. A collection of data
2. Has a method for accessing and manipulating that data

### List of Common Databases
1. Postgre SQL
2. Oracle Database
3. MySQL
4. SOLite

### SQL vs MySQL
1. SQL - Structured Query Language
2. The language we use to talk to databases
3. Most syntax is the same, but not all
4. There is a standard for how SQL should work


## Creating Databases and Tables Lecture
Command: CREATE DATABASE <name>;

Show Databases: SHOW DATABASES;

Dropping Databases: DROP DATABASE <name>;

Using Databases (sort of like cd into them): USE <name>;

Find the current DB you're using: SELECT database();

Create table: CREATE TABLE cats (must always be plural)

Examples:

CREATE TABLE tablename
	(
		column_name data_type,
		column_name data_type
	);

CREATE TABLE cats
	(
		name VARCHAR(100),
		age INT
	);

### Tables
a db is just a bunch of tables --- relational db

tables hold the data / collections of related data

Columns are the headers with Rows being the actual data in the table

Datatypes: 
1. Numeric types
	A. INT - whole number (12, 0, 42, -999)
2. String types
	A. VARCHAR - variable length string (word with varying string lengths, 'coffee', '-9999', 'red apple'), need to specify max length with varchar, like varchar(100)
3. Date types



### Important Tips

`mysql -u root -p`

you dont have to capitalize commands, but people do to show what comes from sql and what comes from the admin