# Item Catalog

- Part of Udacity Full stack web developer nanodegree

# Description

- I developed this application that produces collection of resturants and each resturant has
  its menu Item
- This application provide authentication system Google OAuth and that means only users can
  add , edit , delete items
- Provide logout for users

# Files included

- project.py        -> which the main part of project provide CRUD,Auth,JSON
- database_setup.py -> for database setup and provide access to tables
- lotsofmenus.py    -> sample data used (from instructor notes)
-client_secrets.json->  that file I downloaded it from Google API Console for my App


# Requirments

- Virtual Box
- Vagrant
- Google account for Sign in
- Python , Flask ,  SQLAlchemy

# Run and Installation

1- Download this folder and unzip it
2- cd vagrant and type vagrant up
3- vagrant ssh to get into your virtual machine
4- cd /vagrant/Catalog
5- python database_setup.py
6- python lotsofmenus.py
7- python project.py
8- The app will be on localhost:5000

# Google sign in

1-Follow the steps to create a Google Developers Console project.
2-Then go to the credentials tab and download the client ID as a JSON file.
3-Copy the file to the catalog folder and rename it client_secrets.json.

# JSON endpoints

-localhost:5000/restaurant/JSON
-localhost:5000/restaurant/<int:restaurant_id>/menu/JSON
-/restaurant/<int:restaurant_id>/menu/<int:menu_id>/JSON


# Note
Templates and Sample Data for Insructor Notes on course
