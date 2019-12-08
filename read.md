# presentation-2019
Hello.
My name is Ilia Prihodko. 
I am student of rss school.
And today I want to tell you about database called MongoDB 
`(Next slide)`
There is a quastrion: 
> How to optimize storage of large volumes of data and convenient access to this data?

`(Next slide)`
So databases were created  for resolve this problems.
What is database?
Database is an organized collection of data, generally stored and accessed electronically from a computer system;

For example, some information about site,about your passwords and logins, about dates and adresses.
`(Next slide)`
There is special software called a database management system (DBMS), 
This software used for the orderly storage and processing of large amounts of information/
The most popular DBMS today are 
+ Oracle 
+ MySQL 
+ MongoDB

`(Next slide)`
And about MongoDB I will tell you.

`(Next slide)`
What is MongoDB?

`(Next slide)`
Generally, MongoDB is a document database with the scalability and flexibility.

`(Next slide)`
MongoDB history: 
MongoDB was created by Dwight Merriman. He work with traditional relational database.
`(Next slide)`

The name of the database was derived from the word humongous .It represents the idea of supporting large amounts of data.
`(Next slide)`

MONGODB MAKES DEVELOPMENT EASY
It means that MongoDB’s document model is simple for developers and it is easy to learn and to use.
`(Next slide)`

How it works
`(Next slide)`

At first, a record in MongoDB is a document, which is a data structure composed of field and value pairs. 
So MongoDB documents  use a variant called Binary 
JSON (BSON) that accommodates more data types. The fields in documents are like the columns in a relational database, 
and the values they contain can be a variety of data types, including other documents, or
arrays or arrays of documents.
`(Next slide)`

Collections.
Collections contain sets of documents and function And Collections can contain any type of data, but
the data in a collection cannot be spread across different databases.
`(Next slide)`

The mongo shell is an interactive JavaScript interface to MongoDB which allows users to query and 
update data, and also some administrative operations.
So the shell is a standart component of the open sourse distributions of MongoDB.
 `(Next slide)`
 
Now about basic examples.
`(Next slide)`

Insert a document. In this example we can see 
2 documents that are being inserted into the restaurants collection. Each document have fields: fild "name",fild " stars"  and categories (stored as an array).
`(Next slide)`

Ok, go next.
Create a query.
In this example, we run a simple query to get all of the documents. We find all document and then we store them as an array.
`(Next slide)`

Build an index.
In this example we are building an index on the name field with sort order ascending.
SO Indexes in MongoDB are similar to indexes in other database systems. 
`(Next slide)`

Aggregate.
So using aggregation in MongoDB, we can filter and analyze data based on a given set of criteria.
In this example, we pull all the documents in the restaurants collection that have a category of Bakery
using the $match operator. And after than we group them by their star rating using a $group operator.
`(Next slide)`

Now about main advantages of MongoDB.
`(Next slide)`

At first of course MongoDB stores data in flexible, JSON-like documents.And  it meaning fields can vary from document to document and data structure can be changed over time
`(Next slide)`

Also he document model maps to the objects in your application code,and it making data easy to work with.
Also High availability,horizontal scaling, and geographic distribution are built in and easy to use
And of cpurse it is free to use.
`(Next slide)`

So if you want to learn more details about MongoDB you can visit official page of MongoDB. There is we can see all information
about this database, and learn some features and install this programm.
`(Next slide)`

Thank you for your attention, good bye!
