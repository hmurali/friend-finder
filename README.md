# Friend Finder App
## Description
*Friend Finder* implements friend matching based on the user's responses to a ten question survey. The user reponds to questions with values from 1 (Strongly Disgree) to 5 (Strongly Agree). When the survey is submitted, an existing user record closest to the current user's responses is found and returned. The closest set of user responses is defined as the set with the lowest absolute difference for all ten questions combined. 

*Friend Finder* application is meant to simulate a simple dating app. The application is implemented using a [Node.js](https://nodejs.org/en/) and [Express](https://expressjs.com/) server on the back end and [Bootstrap CSS Framework](https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css) with HTML on the front end. 

## Demo
*Friend Finder* is deployed to Heroku. Click here.

## Installation
To install the app follow these instructions:

`git clone https://www.github.com/hmurali/friend-finder.git
cd friend-finder
npm install`

## Running Locally
To run this app locally and access it in your browser, first set the `PORT` environment variable to the value of your choice. i.e. `export PORT=3000`

After the `PORT` environment variable has been set, run the Node.js application with the following command: `node server.js`

The application will now be running locally on `PORT`, in this case that is port 3000. You can then access it locally from your browser at the URL `localhost:PORT`, in this case `localhost:3000`. 

**NOTE**: If you don't specify a `PORT`, the app will run locally on `localhost:8080` where `PORT=8080`.
