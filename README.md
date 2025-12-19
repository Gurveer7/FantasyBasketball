Folder Layout
Application consists of three folders - backend, frontend, and SQL.

Backend & Production Database

cd backend if you're already in the milestone-3 folder, or cd milestone-3/backend if you're in the root of the repo.

This is where you run all the commands for the server/backend.

First, install the requirements:

pip install -r requirements.txt

Then, to create and populate the database, run

python -m flask --app server init-db

Then, to start the server, run

python -m flask --app server run --port=5001

The console output will tell you the port the server is running on.

Frontend
Note: for the frontend to work properly, the backend must already be running.

Change your current directory to the frontend folder within milestone-3.

cd frontend if you're already in the milestone-3 folder, or cd milestone-3/frontend if you're in the root of the repo.

Install the packages with node package manager (npm) and start the development server:

npm install && npm run start

The website (interface) will be available locally on http://localhost:3000/.

Logging In:
To sign in, please use a valid username:password combo that is pre-initalized.

Sample Logins (username:password):

AaronAndrews:password1
BobbyBrown:password2
You may also register an account and login with it

You will stay signed in while clicking between pages

To logout and login with a different user, refresh the page via ctrl+r and you will be prompted back to the login screen

Sample Database
In order to generate the sample database, navigate to the backend folder

cd backend

From there, run

python server/createSampleDB.py

to generate the sample database.
