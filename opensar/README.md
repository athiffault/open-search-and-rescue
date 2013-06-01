OpenSAR
=======

Open Search and Rescue is an application to help Search & Rescue teams
organize, deploy, and operate. It was developed by Code for Tulsa at the National Day of Civic Hacking.

Using the development environment
---------------------------------
Install requirements

    pip install fabric
    pip install -r requirements.txt

Setup db

    fab syncdb
    fab migrate

Start server

    fab serve

Using the Python shell

    fab shell

Running tests

    fab test

Creating South schema migrations

    fab schema
    fab migrate


Django installable plugin template
Copyright 2013 Jeremy Satterfield
Licensed under GPLv3 see COPYING for license
