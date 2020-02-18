Channels Demo 
==================

A demo application to show a chat server with Django Channels

Features
--------

* For Django 3
* Works with Python 3.8
* Uses Django Channels 2.4.0
* Defined by poetry toml file
* Tests and code-coverage included here

To Run Prototype
------------------
::
Run a redis instance in Docker: 

    $ docker run -p 6379:6379 -d redis:2.8
    
Start application::

    $ poetry run python manage.py runserver
    

Open browser to "http://127.0.0.1:8000/chat/". Type lobby in the textbox and click the button.

Open another browser window to "http://127.0.0.1:8000/chat/lobby/" 

Enter chat messages in the two browsers and watch the messages show up in both windows.