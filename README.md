<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Flask_logo.svg"><br>
</div>

-----------------

# My Flask Tutorial

This is a simple blog application created with the Flask framework that allows a user to register, log in, create posts and edit or delete their own posts.

I used the The [Blog Flask Tutorial](https://flask.palletsprojects.com/en/2.0.x/tutorial/)


# Creation of the Project and Environment Setup
Create a project directory
```
$ mkdir flask-tutorial
```
```
$ cd flask-tutorial
```

Create an environment

**Windows**
```
$ py -3 -m venv venv
```

**macOS/Linux** 
```
$ pyhton3 -m venv venv
````

Activate the environment 

**Windows** 
```
$ venv\Scripts\activate
```
**macOS/Linux**
```
. venv/bin/activate
```

In the activated environment, install Flask
```
$ pip install Flask
```

Create a .gitignore if you will use verson control which ignores files that shouldn't be sent to the repository

```
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
```

# Application Factory and Running the Application

Remember a Flask application is just an instance of Flask class. 

Create a directory called flaskr
```
$ mkdir flaskr
````

and include a file called _ _init _ _.py.

The init file will contain the application factory and shows Python that the flaskr directory should be treated as a package.

Place the code found from the link above in init file.

Move to the flask-tutorial directory and the run the command in your Bash, CMD or Powershell respectively

**Bash**
```
export FLASK_APP=flaskr
```

```
$ export FLASK_ENV=development
```
**CMD**
```
> set FLASK_APP=flaskr
```

```
> set FLASK_ENV=development
```

**Powershell**
```
> env:FLASK_APP=flaskr
```
```
> flask run
```






