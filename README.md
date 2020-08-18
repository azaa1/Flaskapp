# Flask + Python
## Introduction to Flask

![Alt text](img/flaskpython.png?raw=true "Title")

## What is Flask? 

Flask is a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications.

## Prerequisites
- Linux Server
- Python 3.5 or newer
- Install Flask 
```
pip3 install Flask
```


## Folder Structure

- hello 

    contains a minimal 'Hello, World!' application
- simple
    
    contains a minimal application that supports URLs

- variable

    contains a minimal application that supports URLs and receives <variable_name> as a keyword argument. 


## Run Application 

1. Change Directory to application folder you want to run. 
```
cd hello
```
2. Set an environment variable to be exported to child-process.
```
export FLASK_APP=hello.py
``` 
3. Run the application and exposes externally.
```
flask run --host=0.0.0.0
```
4. Open the browser, enter your host's (public) and application port
```
 IP:5000
```

## Project Status

The purpose of this project is to introduce Software Engineers to App Development with Flask and Python. 

## Link to Official Documentations

Python : https://www.python.org/about/apps/

Flask : https://flask.palletsprojects.com/en/1.1.x/

JinJa : https://jinja.palletsprojects.com/en/2.11.x/

Werkzeug : https://werkzeug.palletsprojects.com/en/1.0.x/
