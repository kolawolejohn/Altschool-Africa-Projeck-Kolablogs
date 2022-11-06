Welcome to Kolablogs

to install the application: pip install requirement.txt

NB Ensure you are withing the Altschool-Project structure directory to run all commands

To run the app: flask run

to get random secret
- in the python shell
- import secret
- secrets.token_hex(16)

on using the python shell or flask shell

- flask shell
- db.create_all()

# if that doesn't work for any reason try 
in the python shell
- from kolablogs import app, db
- app.app_context().push()
- from kolablogs.models import User, Post
- db.create_all()

Enjoy the app
