# Data Science and Django Project
## General Admin
Ben 8-24-18
-Deleted project-notes.ipynb and created project-notes.md for easy reading and updating
-Updated .gitignore to include some personal settings files (.DS_store)
-Perhaps we should create a requirements.txt to include any requirements?
## Data Science
## Django
Ben 8-24-18
-Following Sentdex (pythonprogramming.net) tutorial on youtube
-Created Conda Environment to install Django in
-Conda Installed Django <code>conda install django</code>
-Created a Django project within the probable-project <code> django-admin startproject mysite</code>
-In order to hide the secret key created a separate file named secret_settings.py within the same directory and added it to .gitignore. Removed the SECRET_KEY from settings.py and added to secret_settings.py. Added <code>from secret_settings import * </code> within settings.py to compensate for this.
-started webservice on localhost:8000 with troubleshooting on to confirm that django is working.
