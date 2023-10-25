# Python Login System

Form Design — Design a login and registration form with HTML5 and CSS3.
Templates — Create Flask templates with HTML and Python.
Basic Validation — Validating form data that is sent to the server (username, password, and email).
Session Management — Initialize sessions and store retrieved database results.
MySQL Queries — Select and insert records from/in our database table.
Routes — Routing will enable us to associate the URLs with the functions that we will create.

Requirments
Python 3.11.3
MySQL
Python Flask with the command: ```pip install flask```
Flask-MySQLdb with the command: ```pip install flask-mysqld```
1

initial code provided by https://codeshack.io/


\-- pythonlogin
    |-- main.py
    \-- static
        |-- style.css
    \-- templates
        |-- index.html
        |-- register.html
        |-- home.html
        |-- profile.html
        |-- layout.html

```
touch static templates main.py
cd templates && touch index.html register.html home.html profile.html layout.html
```



```
set FLASK_APP=main.py

set FLASK_DEBUG=1

flask run
```