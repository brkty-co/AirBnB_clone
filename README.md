 0x00. AirBnB clone - The console 
The first part of the AirBnB clone project 
First step: Write a command interpreter to manage your AirBnB objects.
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
General
How to create a Python package
How to create a command interpreter in Python using the cmd module
What is Unit testing and how to implement it in a large project
How to serialize and deserialize a Class
How to write and read a JSON file
How to manage datetime
What is an UUID
What is *args and how to use it
What is **kwargs and how to use it
How to handle named arguments in a function


 Command Interpreter is a tool in which we can Create a new object (ex: a new User or a new Place retrieve an object from a file or a database, Do operations on objects, Update the attributes of an object, and Destroy an object.

The console is started executing the file console.py in the main directory. 



create: Creates a new instance of the selected class, saves it (to the JSON file) and prints the id. 
        Usage: create classname. 
        Example create BaseModel
destroy: Deletes an instance based on the class name and id, and saves the change into the JSON file.
         Usage: destroy classname id or classname.destroy(id in string format).
         Example:destroy BaseModel
update: Updates an instance based on the class name and id by adding or updating attribute, and saves the changes into the JSON file. 
       Usage: update classname id attributename attributevalue or   classname.update(id, attributename, attribute value in string format). 
              Example: update BaseModel







