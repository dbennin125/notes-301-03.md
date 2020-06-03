# notes-301-03.md

1. Why would a developer choose to make data models? Models promote agreement on vocabulary and jargon with a clearer scope. It also reduces cost and has higher quality results. 

2. What purpose do CRUD operations serve? Create, Read, Update, Delete. The four basic functions of persistent storage. 

3. What kind of database is Postgres? general purpose object-relational DB management system. 
What kind of database is MongoDB? cross-platform document-oriented database program.

4. What is Mongoose and why do we need it? Object Data Modeling library for MongoDB and Node.js. It's used to translate between objects in code and the representation of those objects in MongoDB. 

5. Define three related pieces of data in a possible application. An example for a store application might be Product, Category and Department. Describe the constraints and rules on each piece of data and how you would relate these pieces to each other. For example, each Product has a Category and belongs in a Department.

For a song App
Name-a string of what the song is.
Time-the lentgh of the song
Albums-array of of albums(including names, times, etc)

Document the following Vocabulary Terms

database-structured set of data held in a computer.

data model-abstract model of elements of data and standardizes how they relate to eachother.

CRUD- standardized use of HTTP Action Verbs (think RESTfful)

schema-Schemas Type can mean 'types' each set with properties. Viewed as a container of objects.

sanitize-(data) computer data that is checked by software first to see if said data is harmful to the database. 

Structured Query Language (SQL)- used to communicate with DB

Non SQL (NoSQL)-database provides a mechanism for storage and retrieval of data that is modeled in means other than the tabular relations used in relational databases. (https://en.wikipedia.org/wiki/NoSQL)

MongoDB-cross-platform document-oriented database program.

Mongoose-Object Data Modeling library for MongoDB and Node.js. It's used to translate between objects in code and the representation of those objects in MongoDB. 

record-composed of fields and contains data about whatever (item) in a database. Usually appear as rows.

document-type of nonrelational databse that stores and queries JSON like documents.

Object Relation Mapping (ORM)-Object-relational mapping (ORM, O/RM, and O/R mapping tool) in computer science is a programming technique for converting data between incompatible type systems using object-oriented programming languages. (source: https://en.wikipedia.org/wiki/Object-relational_mapping#:~:text=Object%2Drelational%20mapping%20(ORM%2C,from%20within%20the%20programming%20language)
