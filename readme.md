_Python Web Frameworks_
==

### **_CONTENTS :_**  


✔ Intro to Web Frameworks

✔ Flask Tutorial

✔ FastAPI Tutorial


_Intro to Web Frameworks_
==
- _**A Web framework**_ is a collection of packages or modules which allow developers to write Web applications or services without having to handle low-level details (protocols, sockets or process/thread management) .

- The majority of Web frameworks are exclusively server-side technology.

    With the increased prevalence of AJAX, some Web frameworks are beginning to include AJAX code that helps developers with the particularly tricky task of programming (client-side) the user's browser. 

- As a developer using a framework, you typically write code which conforms to some kind of conventions that lets you _**plug in**_ to the framework.

    - The communications, infrastructure and low-level stuff of the web application is taken care of by the framework.
    
    - The logic of the application is taken care of in your own code. 

- Frameworks provide support for a number of activities such as 
    - interpreting requests (getting form parameters handling cookies and sessions), 
    - producing responses (presenting data as HTML or in other formats), 
    - storing data persistently    
  

- A web application may use a combination of 

    - a base HTTP application server, 
    - a database, 
    - a template engine, 
    - a request dispatcher, 
    - an authentication module, 
    - an AJAX toolkit.
  

- Flask and FastAPI are some _**Non Full Stack Frameworks**_ whereas Django is a popular _**Full Stack Framework**_. 

## _Flask_

Flask is a micro web framework written in Python.

Components of Flask are :
- Werkzeug
- Jinja 2

### _Werkzeug:_

It is a WSGI(Web Server Gateway Interface) toolkit, which implements requests, response objects, and other utility functions.

### _Jinga:_

Jinja is a fast, expressive, extensible templating engine. Special placeholders in the template allow writing code similar to Python syntax.

## _FastAPI_

FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints.

It is used for developing RESTful APIs in Python. 

FastAPI is based on Pydantic and type hints to validate, serialize, and deserialize data, and automatically auto-generate OpenAPI documents.

It fully supports asynchronous programming and can run with Uvicorn and Gunicorn.
