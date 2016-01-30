# Todo psql application

## Requirements

* Node
* PostgreSQL database running on port 5432. A database needs to be created having one table with 3 fields. 
* Using __pgAdmin__ user permissions should be set to allow read, write, delete operations.	
	+ id:  data type _serial_ which performs auto increment starting at 1. It also ensures the field is _Not Null_. Also set the field to be the _primary key_, 
	+ text:  type _name_,
	+ done: type _Boolean_ 


## Installation

* Clone the Repository
* _npm install_ - install all the node packages listed in the package.json file 
* _bower install_ - installs the front end packages listed in the bower.json file
* Open ../server/config/database.js and enter PostgreSQL database connection details
* _node server.js_
* Browse to _http://localhost:3090_


## Technologies used
  
- [NodeJS](http://nodejs.org/)
- [ExpressJS](http://expressjs.com/)
- [AngularJS](https://angularjs.org/)
- [PostgreSQL](http://www.postgresql.org/) 
- [node-postgre](https://github.com/brianc/node-postgres)
- [Bower](http://bower.io/)




