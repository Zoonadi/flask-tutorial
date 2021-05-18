# My Flask Tutorial

This is a simple blog application created with the Flask framework that allows a user to register, log in, create posts and edit or delete their own posts.

I used the Tutorial found on https://flask.palletsprojects.com/en/2.0.x/tutorial/

# Progress so far
# Creation of the Project and Environment Setup
Create a project directory

$ mkdir flask-tutorial
$ cd flask-tutorial

Create an environment

$ py -3 -m venv venv

Activate the environment

$ venv\Scripts\activate

In the activated environment, install Flask

$ pip install Flask

Create a .gitignore if you will use verson control which ignores files that shouldn't be sent to the repository

venv/

*.pyc
_ _pycache_ _/

instance/

.pytest_cache/
.coverage
htmlcov/

dist/
build/
*.egg-info/

.idea
*.swp
*~

# Application Factory and Running the Application

Remember a Flask application is just an instance of Flask class. 

Create a directory called flaskr

$ mkdir flaskr

and include a file called_ _init _ _.py.

The init file will contain the application factory and shows Python that the flaskr directory should be treated as a package.

Place the code found from the link above in init file.

Move to the flask-tutorial directory and the run the command in your CMD

> set FLASK_APP=flaskr
> set FLASK_ENV=development
> flask run







