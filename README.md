# flask-crud

A simple implementation of the flask CRUD with register and login. In this program you can read/write task in a list, all users can see the task list but only owners (who created the task) can delete/edit the task.

If you want try this program, follow the next step:

### Download or clone the repository

If you want clone the repository, you need installed git.

> git clone https://github.com/solcker/flask-crud.git

Or download source file.

### Create virtual environment

You need Python in your system to create virtual. So follow the steps [here](https://flask.palletsprojects.com/en/2.1.x/installation/#virtual-environments).

### Run the application

At that point you have proyect files and activated virtual environment, now write de next 2 scripts in terminal

> export FLASK_APP=flaskcrud
> export FLASK_ENV=development

Now you need write the next script to initialize the database file:

> flask init-db

And the response is:

> Initialized the database.

The last script is: 

> flask run