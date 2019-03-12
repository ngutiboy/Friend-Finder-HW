Friend Finder Application
Description
This App matches friends based on the user's responses to ten survey questions. The value of these survey questions ranges from 1 (Strongly Disagree) to 5 (Strongly Agree). Once completed and submitted, an existing closest match record based on the lowest absolute difference to the ten questions is returned.

Friend Finder is a simulation of a dating app. The application is implemented using a Node.js and Express server on the back end and the Materialize CSS framework on the front end.

Demo
This App is deployed to Heroku. Please check it out here.

Installation
To install the application follow the instructions below:

git clone git@github.com:ngutiboy/friend-finder.git
cd friend-finder
npm install
Running Locally
To run the application locally and access it in your browser, first set the PORT environment variable to the value of your choice. An example is shown below.

export PORT=3000
After the PORT environment variable has been set, run the Node.js application with the command below.

node server.js
The application will now be running locally on PORT, that is port 3000. You can then access it locally from your browser at the URL at localhost:3000.