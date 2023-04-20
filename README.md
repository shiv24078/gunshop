## Instructions

Commands (Ubuntu with Virtual Enviornment):

    py -m venv venv
    venv\Scripts\activate
    pip install -r requirements.txt
    py manage.py runserver

Commands (Windows without Virtual Enviornment):
In a parent folder:

    git clone https://github.com/shiv24078/gunshop
    pip install -r requirements.txt
    pip install pillow
    py manage.py runserver
    You should have the server running now. press Ctrl break or Ctrl c to shut down the server and thus close the website 
    The website should open in your default browser. If not go to http://127.0.0.1:8000/
    press Ctrl break or Ctrl c in VScode terminal to shut down the server and thus close the website
Note keep in mind that you don't have multiple python just laying around, you gave to select the correct python interpreter with Ctrl+Shift+P and search for Python interpreter and select it or go into +find path and put the path


In core /settings.py the stripe is commented out - just put your own details in here (not all of these are connected to the project)

# Stripe Payment
PUBLISHABLE_KEY = ''
SECRET_KEY = ''

# Admin login
1. http://127.0.0.1:8000/admin
2. username and password = admin

Use Windows