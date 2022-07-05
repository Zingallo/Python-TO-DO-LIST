# Todo-list-python

### Project Details
[Python Flask](http://flask.pocoo.org) Webpage for a TODO list with [AWS RDS/MYSQL Backend](https://aws.amazon.com/rds/mysql/). Using [SQLAlchemy](http://flask-sqlalchemy.pocoo.org/) for database connection as well as object mapping. Flask will be used for the server and displaying. [Flast-RESTPlus](http://flask-restplus.readthedocs.io/en/stable/) will be used for anyone trying to call via API's. Pages are in HTML with CSS styling. Inserting todos with date is done with natural language via [Recurrent](https://github.com/kvh/recurrent).As instructed it is able to do the following .
1. Signup and login to register and authenticate a user that wishes to create a to-do list.
2. A feature to add a task and display tasks in one’s to-to list only after they have logged-in successfully.
3. Once logged-in, the app should display the tasks that have been added by the logged-in user and provide an
option to edit or delete existing tasks on the list.
### Core Architecture
You need to create three tables namely todo,user,user_log_activity for the database TodoList.

### How to use API
[Flast-RESTPlus](http://flask-restplus.readthedocs.io/en/stable/) was used to build a REST server so that the list and other information is accessible from API's.

In your chosen API client (curl via terminal, [Postman](https://www.getpostman.com) or [Insomnia](https://insomnia.rest/) do a GET request for `<base_url>/todo_api/<your_api_key>`. You must add an api_key to your user in the database. Full list of API available at a later time.








# BSG-TO-DO-LIST
