# Introduction

The goal of this project is to create a random password Generate by using **django**

![Default Home view](Readme_files/Home_page.png)

### Main features

* Separated dev and production settings

* Example app with custom user model

* Bootstrap static files included

* User registration and logging in as demo

* Procfile for easy deployments

* Separated requirements files

* SQLite by default if no env variable is set

# Usage

To use this template to start your own project:

### Existing virtualenv

If your project is already in an existing python virtualenv first install django by running

    $ pip install django
    
And then run the `django-admin.py` command to start the new project:

    $ django-admin.py startproject \
      --template=https://github.com/sa24449/Online_Password_Generator-Django.git \
      --extension=py,md \
      <Password_generator>
      
### No virtualenv

This assumes that `python` is linked to valid installation of python 3 and that `pip` is installed is valid
for installing python  packages.

Installing inside virtualenv is recommended, however you can start your project without virtualenv too.

If you don't have django installed for python 3 then run:

    $ pip install django
    
And then:

    $ python -m django startproject \
      --template=https://github.com/sa24449/Online_Password_Generator-Django.git \
      --extension=py,md \
      <Password_generator>
      
      
After that just install the local dependencies, run migrations, and start the server.



## Password Generator -Django

# Getting Started

First clone the repository from Github and switch to the new directory:

    $ git clone git@github.com:sa24449/Online_Password_Generator-Django.git

Move to Project directory:

    $ cd Online_Password_Generator-Django
    
Activate the virtualenv for your project.
    
Install project dependencies:

    $ python manage.py make migrations
    
    
Then simply apply the migrations:

    $ python manage.py migrate
    

You can now run the development server:

    $ python manage.py runserver

In Terminal you can find project is running on your local host on successful run 
   
    $ http://127.0.0.1:8000/