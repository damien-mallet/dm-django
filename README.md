# dm-django
This repository aim to build a simple and configurable Django boilerplate to kickstart a website development

## 1. Install Python and Django
Python Installation: Ensure that Python is installed on your system. You can download it from python.org.
Install Django: Once Python is installed, you can install Django using pip:

`$ pip install django`

## 2. Create a Django Project
Navigate to your desired directory: Open your terminal and navigate to the directory where you want to create your project.
Start a new Django project: Use the following command to create a new project:

`$ django-admin startproject project`

## 3. Run the Development Server

`$ cd app`

`$ python manage.py migrate`

`$ python manage.py runserver`

## 4. Create a Django App
Django projects are composed of one or more apps. To create an app within your project, use:

`$ python manage.py startapp app`

## 5. Register the App
After creating an app, you need to register it in your project. Open myproject/settings.py and add your app to the INSTALLED_APPS list:

`INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'app',
]`