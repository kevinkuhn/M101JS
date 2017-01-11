# M101JS: MongoDB for Node.js Developers

## Week 1

### What is MongoDB?

* Document Database
* JSON to store data
* Dev can design database models to support common data access patterns
* Combining Content without JOINs accross tables possible
* MongoDB can be scaling out to different servers (nodes) without the need of scaling up
* Supports agile development process

### Overview of Building an App with MongoDB

mongo <--> MongoDB <--> app <--> clients

* mongo shell needed to manage MongoDB
* MongoDB (C++)
* app (Node.js, C++, V8 JavaScript)

### JSON

* Keys have to be strings
* Keys and values are separated by ":"
* Fields are separated with "," as delimiter
* JSON objects are opened and closed using curly braces {}
* Value types: String, number, boolean, array value
* Nesting objects are possible
* More json.org

### BSON

* MongoDB stores data as BSON (binary JSON, http://bsonspec.org/)
* MongoDB drivers send and receive BSON
* In MongoDB everything is stored as BSON
* MongoDB drivers map BSON to whatever the native data types is
* BSON is lightweigt, traversable and efficient

### CRUD

* Create
* Read
* Update
* Delete

### Mongo commands

* mongod | start server
* mongo | start mongo shell
* mongo shell > help | shows help documentation
* show dbs | shows databases
* use nameOfTheDatabase| use a database (even if does not yet exist)
* db.collection.insertOne()| create a new collection
* db.collection.find()| shows the whole content of the collection
* db.collection.find().pretty()| shows the whole content of the collection nicely formatted


