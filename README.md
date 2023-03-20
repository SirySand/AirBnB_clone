This is the AIRBNB clone project aiming to deploy on our server a simple copy of the airbnb website.

DESCRIPTION OF THE PROJECT
At the end of the project, we are supposed to have an web application with four elements:

A command interpreter to manipulate data without a visual interface, like in a Shell (perfect for development and debugging)
A website (the front-end) that shows the final product to everybody: static and dynamic
A database or files that store data (data = objects)
An API that provides a communication interface between the front-end and your data (retrieve, create, delete, update them)

DESCRIPTION OF THE COMMAND INTERPRETER / CONSOLE
The command interpreter also called the console in our project helps developers to manipulate data with commands prompts like in a Shell prompt 
but with a specific use case. It will help with creating, retrieving, updating and also deleting objects. It will also create data models and 
store and persist objects to a JSON file. It will be the tool to validate the storage engine. This last will give us a abstraction between 
"objects" and "how they are stored and persisted". That means that we will not have to worry about how objects are stored when we will be using
the console or the RestAPI we'll build later.
