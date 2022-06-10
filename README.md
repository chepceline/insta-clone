## Description

Instaclone is a web application that is like instagram. Users get can view photos uploaded by other users. users can also like and comment on photos.
## Features

The home page allows users to see various users:
User can see other users who have logged in follow and also logout
Users can also search for images based on categories

## View Live Site here

https://celgram.herokuapp.com/

## Technologies Used

- Python 3.8
- Django MVC framework
- HTML, CSS and Bootstrap
- JavaScript
- Postgressql
- Heroku
## Prerequisite

The insta-clone project requires a prerequisite understanding of the following:

Django Framework
Python3.8
Postgres
Python virtualenv

## Setup and installation

# Clone the Repo from

https://github.com/chepceline/insta-clone.git

# Activate virtual environment

Activate virtual environment using python3.6 as default handler virtualenv -p /usr/bin/python3.8 venv && source venv/bin/activate

# Install dependancies

Install dependancies that will create an environment for the app to run pip3 install -r requirements.txt

# Create the Database

- psql
- CREATE DATABASE insta;
# .env file

Create .env file and paste paste the following filling where appropriate:

SECRET_KEY = '<Secret_key>'
DBNAME = 'insta'
USER = '<Username>'
PASSWORD = '<password>'
DEBUG = True

# Run initial Migration

python3.8 manage.py makemigrations gallery
python3.8 manage.py migrate

# Run the app

python3.8 manage.py runserver
Open terminal on localhost:8000
# knownbugs
Some images could no load

# Contributors
- Damaris Chepchirchir

# Contact Information
chepceline25@gmail.com