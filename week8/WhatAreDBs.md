What is a database?

Collection of related info eg fb user base.

A database design is its schema.

Database Management Systems (DBMS):

Software that helps users create and manage databases and ensures the fulfilment of
security, management of information whilst interacting with other software.

C.R.U.D: CREATE | READ | UPDATE | DELETE -> main operations a good DBMS should perform

Two types of databases:

- Relational Databases: SQL -> organizes data into tables
- Non-Relational : noSQL, not just SQL -> other than tables eg graphs, JSON

SQL -> Structured Query Language

SQL is not necessarily portable from one RDBMS to the other.

NRDBMS: mongoDB, firebase (no standard language)

Database Query: Requesting the DBMS for information 

In relational databases we have columns and rows in our tables where
- column : single attribute
- row : entry into the database
- primary key : uniquely identifies a specific row 
- surrogate key : a value we can use to represent a specific row in a database. This type of value does not have any use in the real world
- natural key : this value has a mapping to the real world eg SSN, CNIC
- foreign key : an attribute you can store in a database table that can link you to another table, this is a primary key on another table
- a table can have more than one foreign branch on it 
- we can define relations between a type of data in the same table 
- composite key : is made up of two or more attributes where only together can these uniquely identify a row 


SQL BASICS:

SQL is a hybrid language where 4 languages are mashed up into one.

These include:
- Data Query Language DQL: what info you want from your database
- Data Definition Language DDL: used to define what the layout of the database will be
- Data Control Language DCL: used to control access to a database
- Data Manipulation Language DML: used for inserting, updating and deleting data

Query is the set of instructions given to a database.

