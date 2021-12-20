Cómo añadir autenticación a su aplicación con Flask-Login
By Anthony Herbert
https://www.digitalocean.com/community/tutorials/how-to-add-authentication-to-your-app-with-flask-login-es

Published onNovember 12, 2020

.
└── flask_auth_app
    └── project
        ├── __init__.py       # setup our app
        ├── auth.py           # the auth routes for our app
        ├── db.sqlite         # our database
        ├── main.py           # the non-auth routes for our app
        ├── models.py         # our user model
        └── templates
            ├── base.html     # contains common layout and links
            ├── index.html    # show the home page
            ├── login.html    # show the login form
            ├── profile.html  # show the profile page
            └── signup.html   # show the signup form

instalar
pip install flask flask-sqlalchemy flask-login

Crear
export FLASK_APP=project
export FLASK_DEBUG=1

y ejecutar: 
flask run 