# moDBap
The ABAP mongo DB API

## Needed 3rd party software
* Mongo DB >= 2.0.2 http://www.mongodb.org
* Python 2.7.x http://python.org
* PyMongo 2.1.1 (Python Mongo DB driver) http://api.mongodb.org/python/current/
* Sleepy.Mongoose (Mongo DB HTTP interface) https://github.com/mongodb-labs/sleepy.mongoose

## Needed packages
* ABAP JSON document class >= 0.2.5 https://github.com/se38/zJSON
* moDBap (this project)

## Installation
* For 3rd party software -> see manuals
* You may install mongo DB and Sleepy.Mongoose also on a virtual machine.
* import Nugget with [SAPlink](http://www.saplink.org)

Start Mongo DB 
```
./mongod
Sun Feb 12 12:34:01 [initandlisten] waiting for connections on port 27017
```
Start Sleepy.Mongoose 
```
python httpd.py
listening for connections on http://localhost:27080
```

## Short Mongo DB Documentation (Booklet)
Download from 10gen: http://www.10gen.com/static/downloads/mongodb_qrc_booklet.pdf

## Usage
see wiki ( https://github.com/se38/moDBap/wiki )

## License
This software is published under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)
