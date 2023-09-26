# Web_Application_Project
## The code is written in python and html Languages.
### A Django Web Application
#### The purpose of this project was to setting up the Learning Log Project.
Behind the scenes, today’s websites are rich applications that act like fully developed desktop applications. With Python, there's a robust set of tools named Django, designed explicitly for building web applications. This repository will show you how i 
build the structure of an online journal system that lets you document and track information you’ve learned about various topics,
(like personal blog).

# In the upcoming sections you will see what had been the code:
Full understanding of the Django framework and its capabilities.

Setting up a Django project for the Learning Log application.

Defining models for the data.

Utilizing Django's admin system.

Creating interactive views and templates.

deploying the project on a live server.

#### Objective: Develop a web application named Learning Log.
#### Functionality: Users can log topics of interest and make journal entries as they learn about each topic.
#### User Interface: A homepage describing the site, with options for users to register or log in. Post-login, users can create topics, add new entries, and read/edit existing entries.

## Setting up the Virtual Environment:
Django projects thrive in a virtual environment. This isolated environment ensures your project's libraries don't interfere with other Python projects, especially when deploying the project to a live server.
### To work with Django, we'll utilize a virtual environment, providing an isolated workspace:
#### macOS & Linux:
source ll_env/bin/activate

#### Windows (cmd):
ll_env\Scripts\activate

#### Windows (PowerShell):
.\ll_env\Scripts\Activate

### Deactivation:
deactivate

## Installing Django:
pip install django

## Creating a Django Project:
django-admin startproject learning_log .

##### The above command generates a new directory learning_log and a manage.py script. You'll mostly interact with three key files inside the learning_log directory:

#### settings.py - Contains configurations for Django.
#### urls.py - Determines the URLs for the project.
#### wsgi.py - Web Server Gateway Interface, helps in serving Django files.


### Creating the Database:
Django uses a database for storing project data. To set this up:

python manage.py migrate

### Viewing the Project:
Check if Django set up the project correctly:

python manage.py runserver

## With these steps, you should be able to set up, run, and view the Learning Log Django project in your local development environment.


<img width="385" alt="image" src="https://github.com/Masanbat12/Web_Application_Project/assets/93978448/f3d7f0e3-6a16-4c9b-a5fb-d5b2b41691c6">

##### The code is better, but its basic form at the beginning takes this form before all the plugins I added later, good luck if you want to use this code for development your own learning log.
