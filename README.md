# Gallery of the Globe 
###### By: Jacob Janowski, Husham Alammar

## Database project for UIC
Web app that that allows users to make an account, post pictures of wherever they are, comment on other posts. A simple blog page of photos.

## View Project
Visit the website [here](https://fierce-eyrie-65571.herokuapp.com/) to see the deployed version of our application.

## Getting Started
**_THIS INSTALLING IS FOR Windows_**. Make sure you have all the necessary frameworks installed when running our application. Before installing, check to see if you have them installed already.
Will be using [MongoDB](https://www.mongodb.com/try/download/community) and [NodeJS](https://nodejs.org/en/download/). 

After downloading, run the following commands to confirm:

`node -v`

`npm -v`

Once confirmed, next we go to installing the program. Go ahead and download the _.zip_ file for this repo. 

Once downloaded, go to your 'Program Files' and find the directory MongoDB. 

The path should be similar to this:

`Program Files/MongoDB/Server/4.0/bin`

From in here, you will see all of the MongoDB executables in order for our database to be linked to our program.

## Running the Program
1. Go to `Program Files/MongoDB/Server/4.0/bin` and run the following command:
`./mongod`
2. Go into the directory where the _app.js_ file is located from the _.zip_ file. 
Once there, run the following command:
`node app.js`
You will receive a message in console showing 'Gallery of the Globe server is live'. 
3. Go ahead and open a browser and in the URL, type in `localhost:3000`. You should now see the locally deployed version of the program!
4. To view all database information regarding tables, users, posts, comments, etc., go back into `Program Files/MongoDB/Server/4.0/bin` and run the Mongo Shell by typing the command `./mongo`.

## Interacting with Mongo Shell
This is where we use CRUD fundamentals to be able to make changes on our web app via Mongo Shell commands. Here are some instructions to play around with and notice changes you've made:

Within the Mongo Shell (again, that's within the path listed above and then run `./mongo`), let's start by viewing the databases and using one of them.


## Built With
* [Bootstrap 3](https://getbootstrap.com/docs/3.3/css/) - The CSS framework used
* [Font Awesome](https://fontawesome.com/v4.7.0/) - Fonts used 

### Front End
* HTML
* CSS
* JavaScript
* JQuery

### Back End
* MongoDB
* Mongoose
* Passport.js
* Express
* NodeJS
* Connect-Flash
