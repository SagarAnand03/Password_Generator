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

## Password Generator -Django

# Getting Started

First clone the repository from Github and switch to the new directory:

     git clone https://github.com/sa24449/Online_Password_Generator-Django.git

Move to Project directory:

     cd Online_Password_Generator-Django
    
Activate the virtualenv for your project.
    
Install project dependencies:

     python manage.py make migrations
    
    
Then simply apply the migrations:

     python manage.py migrate
    

You can now run the development server:

     python manage.py runserver

In Terminal you can find project is running on your local host on successful run 
   
     http://127.0.0.1:8000/
