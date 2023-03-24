# Register-Login-Logout

This repo was created as a practice on cretaing a User register, login, logout basic task.
This app was created using these dependencies
--> express, bcrypt, passport, flash, session, method-overriding packages

Code explanation

The code starts by requiring the modules that are needed for this application.
The code then defines a users array, which will be used to store all of the user data in this app.
Next, it creates an express object and sets up some routes for the app. 
Then it initializes passport-config with a function called initializePassport.
This function is passed into passport as an argument and uses find() to search through all of the users
in order to find any user who has their email set to "test@example.com". 
It also finds any user whose id matches that of another user's id. 
The result is stored in a new variable called users . Finally, it starts using session , flash , and urlencoded.
The code is a snippet of code that would be used in a Node.js application with the NODE_ENV environment variable set to "production".
The purpose of this snippet is to use the passport-config module, which will initialize the user's passport.
The following code demonstrates how you can use dotenv to load configuration values
  ===>>  .env file: const dotenv = require("dotenv").config(); const methodOverride = require("method-override");
  
The code starts by initializing the app. The code then uses passport to authenticate a user with local authentication.
The code then sets up the success and failure redirects for when a user is authenticated or not. 
Next, it creates an array of users that will be saved in the database on successful login and registration. 
The last line calls bcrypt to hash a password before saving it in the database.
The code attempts to create a login function that checks if the user has authenticated. 
If they have, it will redirect them to the homepage. 
If not, it will redirect them to a failure page where they can try again. 
The code is also supposed to create a register function which will check if the user has authenticated before attempting registration.

The code starts by checking if the user is logged in.
If they are, then it redirects them to the index page. Otherwise, it checks if they're not authenticated and sends them to the login page.
The code starts by checking if there's an error with authentication before sending them back to the register page. 
If there isn't an error, then it displays a welcome message on the index page and redirects back to /login .
The code attempts to make the user log out of the application. 
The code above will redirect them to the login page if they are not logged in or it will redirect them to the register page if they are already logged in.
