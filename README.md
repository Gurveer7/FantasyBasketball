# Project Folder Layout

The application consists of three main folders:
- backend
- frontend
- SQL

---

## Backend & Production Database

Navigate to the backend directory:

cd backend

If you are in the root of the repository:

cd milestone-3/backend

All server and backend-related commands are run from this directory.

### Install Requirements

pip install -r requirements.txt

### Create and Populate the Database

python -m flask --app server init-db

### Start the Server

python -m flask --app server run --port=5001

The console output will display the port the server is running on.

---

## Frontend

Note: The backend must be running for the frontend to work properly.

Navigate to the frontend directory:

cd frontend

If you are in the root of the repository:

cd milestone-3/frontend

### Install Dependencies and Start the Development Server

npm install && npm run start

The website interface will be available at:
http://localhost:3000/

---

## Logging In

To sign in, use a pre-initialized username and password combination.

### Sample Logins

AaronAndrews:password1  
BobbyBrown:password2  

You may also register a new account and log in using your own credentials.

You will remain signed in while navigating between pages.

To log out and sign in with a different user, refresh the page using Ctrl + R to return to the login screen.

---

## Sample Database

To generate the sample database, navigate to the backend directory:

cd backend

Then run:

python server/createSampleDB.py

This will generate and populate the sample database.
