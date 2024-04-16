# SQL-MongoDB
SQL stands for structured query language.
I is the standard language for communicating with relational database system management system
It was developed in the early 70's (1973) to retrieve data from IBM
A relational database orgarnises datainto tables like an excel spreedsheet, where columns contain attributes or types of data while each row represents an individualrecord or datapoint with it's unique ID known as a primary key

SQL Datatypes
SQL datatypes are used to specify the type of data that can be stored in ecah column of a table.
For instance lets say we have a table and thistable needs to have a namme and a datatype
We specify the datatypes sfor each and every column of a particular table
When creating a table , when we want a speccific type of values to be inserted in a column like numbers then you need to specify the datatype as int.
If you want to insert a text then its datatype will be varchar

Different types of datatypes
They can be devided into three categories:
String-vachar
Numeric-int, boolen, double
Date and time-date, time, datetime, year

String datatype
The most commonly used string datatype is the VarChar
VarChar(size): is the variable length string that can contain letters, numbers and special characters.
The size parameter specifies the maximum string length in characters, can be from 0 to 65535

Numeric Datatype
INT(size): A medium integer. Signed range is from -21.47,483,648 to 21.47,483.647
Unsigned range starts from 0mto 4294967295
The size parameter specifies the maximum display width which is 255

Date and time datatypes
Date: a date format is YYYY-MM-DD.
The supported range is from "1000-01-01" to "9999-12-31"
Time: a time format is hh:mm:ss 
The supported range is from "-838:59:59" to"838:59:59"
Date time: A date time combination format is YYYY-MM-DD hh:mm:ss
The supported range is from "1000-01-01 00:00:00" to "9999-12-31 23:59:59"

Year: A year is in four-digits format.
Values allowed in a four digit format: 1901 to 2155 and 0000

Introduction to MongoDB

MongoDB is a cross-platform, document-oriented database that provides, high performance, high availability, and easy scalability. MongoDB works on concept of collection and document.

Database
Database is a physical container for collections. Each database gets its own set of files on the file system. 
A single MongoDB server typically has multiple databases.

Collection
Collection is a group of MongoDB documents. It is the equivalent of an RDBMS table. 
A collection exists within a single database. Collections do not enforce a schema. 
Documents within a collection can have different fields. 
Typically, all documents in a collection are of similar or related purpose.

Document
A document is a set of key-value pairs. Documents have dynamic schema. Dynamic schema means that documents in the same collection do not need to have the same set of fields or structure, and common fields in a collection's documents may hold different types of data.
The following table shows the relationship of RDBMS terminology with MongoDB.
