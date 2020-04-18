#Django Boilerplate Project
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/Django?style=flat-square)
![PyPI - Status](https://img.shields.io/pypi/status/django)
![APM](https://img.shields.io/apm/l/vim-mode)


This repository is a boilerplate Django project for quickly getting started.

This project includes:
1. Multiple settings for development and Production environment.
2. Email based authentication instead of username.
3. Python Decouple .env settings file.

### Steps:

    
1.Download or clone this repository.
    
    git clone https://github.com/p4l4s6/Django_Boilerplate_Project.git
2.Go to project folder.    
    
    cd Django_Boilerplate_Project/
3.Create virtual environment.
    
    python3 -m venv venv 
4.Activate virtual environment.

**Windows:**

    \env\Scripts\activate 
**Linux:**

    source venv/bin/activate
5.Install requirements.

    pip install -r requirements.txt
    
6.Configure your Environment variables in **.env** file.

7.Make Migrations.

    python manage.py makemigrations
    python manage.py migrate
8.Run python server.

    python manage.py runserver
