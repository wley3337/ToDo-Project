# ToDo project

The goal of this project is to build out a ToDo app with frontends and backend APIs using different technologies as I learn and grow.  

# Frontends:

* [React with Redux/Sagas/TypeScript/Hooks](https://github.com/wley3337/todo-react-redux-saga) <-- use this one when spinning up the backend as it is the most complete (error displaying to user still to come.). 
* [React with Redux/Thunk/TypeScript/Hooks](https://github.com/wley3337/todo-react-redux) <-- this is partial (only has login, account and list create )


# Backends: 

* [Rails API PostgreSQL](https://github.com/wley3337/rails-todo-api) <--- you can use this repo for all migrations (there is no seed data)
* [Express API PostgreSQL](https://github.com/wley3337/todo-express-api) <--- still need to add db migration and creation
* [Python (Flask) API PostgreSQL](https://github.com/wley3337/todo-python-api) <--- still need to add db migration and creation

## All Backends require a PostgreSQL DB

***DEV DB***

* Name: `todo_rails_api_development`
* Tables: 
    * users { first_name: string, last_name: string, username: string, password_digest: string, created_at: datetime, updated_at: datetime }

    * lists { user_id: integer, heading: string, display_order: integer, created_at: datetime, updated_at: datetime }

    * to_dos { list_id: integer, title: string, description: string { default: ""}, due: datetime, created_at: datetime, updated_at: datetime }

***TEST DB***
* Name: `todo_rails_api_test`
* Tables: 
    * users { first_name: string, last_name: string, username: string, password_digest: string, created_at: datetime, updated_at: datetime }

    * lists { user_id: integer, heading: string, display_order: integer, created_at: datetime, updated_at: datetime }

    * to_dos { list_id: integer, title: string, description: string { default: ""}, due: datetime, created_at: datetime, updated_at: datetime }



