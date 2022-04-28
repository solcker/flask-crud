# flask-crud

A simple implementation of flask CRUD with register and login. With this code, we can read/write tasks in a list. All users can see the task list, but only owners of tasks can delete/edit tasks.

If you want to try this program, follow the next steps:

### Download or clone repository

If you want to clone a repository, you need to install git and use the next command or download source files:

> git clone https://github.com/solcker/flask-crud.git

### Create virtual environment

You need Python in your system to create a virtual environment. So follow the steps [here](https://flask.palletsprojects.com/en/2.1.x/installation/#virtual-environments).

### Run the application

At this point, you have files and activated virtual environment, now write the next two commands in terminal.

> export FLASK_APP=flaskcrud

> export FLASK_ENV=development

Now you need to write the next command to initialize the database file:

> flask init-db

The response is:

> Initialized the database.

The last command is:

> flask run