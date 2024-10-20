Step 1: Install Python and Django
Ensure you have Python installed on your system.

Step 2: Then,install Django using pip:pip install django

Step 3: Create a New Django Project
Once Django is installed, create a new project using the following command:django-admin startproject projectname

Step 4: Start the Development Server
Navigate into your project folder and start the server:cd projectname
python manage.py runserver

Step 5: Add the App to Settings
INSTALLED_APPS = [
    # Other installed apps
    'appname',
]
