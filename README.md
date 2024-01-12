## The AirBnB Clone Project

Project Description
---

The AirBnB Project is the first project we are working on towards building our first full web application. The AirBnB clone.

This project:
1. will put in place a parent class(called Basemodel) to take care of initialisation, serialization and deserialization of future instances.
2. will create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
3. will create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
4. will create the first abstracted storage engine of the project: File storage.
5. create all unittests to validate all our classes and storage engine


Python objects (Data) generated are stored in a json file and can be accessed with the help of the json module in python


Command Interpreter Description
---

This Application is similar to the Bash shell but in this case, we have been limited to a specific use-case. In our case, we want to be able to manage the objects of our project by:

1. Creating a new object (ex: a new User or a new Place)
2. Retrieving an object from a file, a database etc…
3. Doing operations on objects (count, compute stats, etc…)
4. Updating attributes of an object
5. Destroying an object.

How the Application Works
---
The application works in both interactive and non-interactive mode.

1. In the Interactive mode it works like this:
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$

2. In the non-interactive mode it works like this:
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$


AUTHORS
---
Olivia Ahinee Tetteh | Email: oatetteh@gmail.com
Addai Christopherr | Email: addaichristopher1@gmail.com

