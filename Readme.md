# RestFul_Api with JWT
+ This is a simple todo restful api with jwt authentication
+ **`RESTFul`** -> Representational state transfer (REST) is a software architectural style that describes a uniform interface between physically separate components, often across the Internet in a client-server architecture. 
  
## Imports
+ `make_response` -> to make the response
+ `request` -> to receive the response
+ `render_template` -> to generate a output form
+ `jsonify` -> to convert the data into json
+ `wraps`
  + wraps() is a decorator that is applied to the wrapper function of a decorator.
  + A decorator is a function that takes in another function as a parameter and then returns a function Decorators provide a simple syntax for calling higher-order functions
+ `flask_sqlalchemy` -> flask & sqlalchemy interface
+ `uuid` -> generating unique numbers
+ `werkzeug.security` -> for hashing password and verify it
+ `jwt` -> Json Web Token
  
## Setup
+ `app.app_context().push()` -> Inorder to work outside the application context
+ `app.config['SQLALCHEMY_DATABASE_URI']` = 'sqlite:////{file_location}/{db_name}.db'
+ Create required models
+ `db.create_all()` -> command to create the database (before the flask app is instantiated)
+ Run ->`python api.py`
