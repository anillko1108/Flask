# Flask
## What is Flask?

Flask is an API of Python that allows us to build up web-applications. It was developed by Armin Ronacher. Flask’s framework is more explicit than Django’s framework and is also easier to learn because it has less base code to implement a simple web-Application. A Web-Application Framework or Web Framework is the collection of modules and libraries that helps the developer to write applications without writing the low-level codes such as protocols, thread management, etc. Flask is based on WSGI(Web Server Gateway Interface) toolkit and Jinja2 template engine.
- Flask has two main dependencies. The routing, debugging, and Web Server Gateway
Interface (WSGI) subsystems come from Werkzeug, while template support is provided
by Jinja2. Werkzeug and Jinja2 are authored by the core developer of Flask. 
## Installation of Flask
### Install virtualenv for development environment
virtualenv is a virtual Python environment builder. It helps a user to create multiple Python environments side-by-side. Thereby, it can avoid compatibility issues between the different versions of the libraries.

The following command installs virtualenv

        pip install virtualenv
        
This command needs administrator privileges. Add sudo before pip on Linux/Mac OS. If you are on Windows, log in as Administrator. On Ubuntu virtualenv may be installed using its package manager.

        Sudo apt-get install virtualenv
        
Once installed, new virtual environment is created in a folder.

        mkdir newproj
        cd newproj
        virtualenv venv

To activate corresponding environment, On Windows, following can be used

        venv\scripts\activate
        
We are now ready to install Flask in this environment.

        pip install Flask
        
The above command can be run directly, without virtual environment for system-wide installation.
