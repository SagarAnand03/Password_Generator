# Introduction

The goal of this project is to create a random password Generate by using **django**

![Default Home view](Readme_files/Home_page.png)

### Main features

* creates random or customized passwords for users. It helps users create stronger passwords that provide greater security for a given type of access.

* user can select length of password between  6-14

* User can select uppercase , Number , Special Character by enable check Box  according to need

* Where result will appear after triggering the Generate Password Button in following format:

![Default Home view](Readme_files/output_page.png)

* User can also access information by triggering About Button

![Default Home view](Readme_files/about.png)

## Version(**Used while making project**) 

Python:
     
     Python 3.9.9
     
     
PIP :
   
     pip 21.2.4
     
     
Django:
     
     Django 4.0.1



## Install project dependencies:(**Ignore if you have following dependencies in you computer**)

Python:
     
     https://www.python.org/
     
     
PIP :
   
     python get-pip.py
     
     
Django:
     
     python -m pip install Django

# Password Generator -Django

## Getting Started

First clone the repository from Github and switch to the new directory:

     git clone https://github.com/sa24449/Online_Password_Generator-Django.git
     

Move to Project directory:

     cd Online_Password_Generator-Django
     
    
Then simply apply the migrations:

     python manage.py migrate
    

You can now run the development server:

     python manage.py runserver
     

In Terminal you can find project is running on your local host on successful run  
   
     http://127.0.0.1:8000/
