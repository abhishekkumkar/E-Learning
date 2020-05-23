# Introduction
Project was created by participating team in extension engine spring camp.
E-Learning is scalable web application written in python (django).
E-Learning was designed to provide pleasant experience for users.
# Installation
Assuming you use virtualenv, follow these steps to download and run the
e-learning application in this directory:

    $ git clone 
    $ cd eLearning
    $ virtualenv venv
    $ source ./venv/bin/activate
    $ pip install -r requirements
    $ python manage.py migrate
    $ python manage.py runserver

* Initial data supports 3 types of users for testing purposes:
    * User (username=user, password=letmein123)
    * Professor (username=professor, password=letmein123)
    * Admin (username=admin, password=letmein123)
    * Visit http://127.0.0.1:8000/

