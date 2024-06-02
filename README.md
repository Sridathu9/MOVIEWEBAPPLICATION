# MOVIEWEBAPPLICATION

Installation
To run the Web Application on your local system download Node.js - https://nodejs.org/en/download/ . This will give you access to the node package manager which is essential to run the project .

npm install
Open the terminal and type in npm install, to install all the dependencies.
Run: npm start
Open http://localhost:8000 to view it in the browser.
🚩 Building project :
1. npm init
Initialize project using npm init

2. npm install express
Install express using npm install express

3. npm install ejs
Install ejs using npm install ejs

Include following lines to use ejs in index.js
app.set('view engine','ejs'); app.set('views','./views');

4. npm install express-ejs-layouts
Install the library npm install express-ejs-layouts

Include following lines to use ejs in index.js
const expressLayouts = require('express-ejs-layouts'); app.use(expressLayouts);

5. npm install mongoose
Mongoose is a MongoDB object modeling tool designed to work in an asynchronous environment. Mongoose supports both promises and callbacks. Install mongoose npm install mongoose

6. npm install cookie-parser
For reading and writing into cookies, we will be using a library called cookie-parser. Install the library using the command npm install cookie-parser

7. npm install passport
Passport is an authenticated middleware for Node.js Install the passport.js library using the command npm install passport

8. npm install passport-local
Install the passport-local using the command npm install passport-local

9. npm install express-session
Install the library using the command npm install express-session in the terminal.

10. npm install connect-mongo
MongoDB session store for Connect and Express written in Typescript Install the connect-mongo using npm install connect-mongo

11. npm install dotenv
Install npm install env for .env file

📌 Prerequisites
1. System requirement :
Any system with basic configuration.
Operating System : Windows / Linux / Mac
2. Software requirement :
Updated browser
Node.js installed (If not download it here).
Any text editor of your choice.
Technologies used
Javascript
NodeJS,ExpressJS
MongoDB for database
passportjs library for authentication
OMDB API
HTML,CSS,ejs
Features
Sign In and Sign Up autjentication
Built using MVC Architecture
User can search a movie name and get details of that movie
Details of movies are fetched from API
User can add a movie to a playlist
Playlist is completely private and user can see it after login only
Without sign in user can search movie and get details but cannot add to playlist
