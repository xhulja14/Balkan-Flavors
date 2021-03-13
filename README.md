
## Balkan Flavours (Recipe cookbook Project)

## This project is created to put into practice the skills learned during the course, especially with the use of Flask and Mongo Db backend coding, and frontend framework called Materialize.
I decided to create a recipe app where the users will be able to see recipes, add recipes, update them and delete them.
Using the CRUD calls to a Mongo database this project is very functional and working as expected.
With the help of Materialize framework makes it easier for archiving good user experience.
This project is made for users to view recipes, create recipes, update their own recipes, and delete their recipes.

## UX
## Users stories

* Users can see recipes.
* Users can register and create an account.
* Users can add recipe.
* Users can update their recipes.
* Users can delete a recipe.
* All visitors should be able to have all the information needed for a recipe such as ingredients, directions of cooking and of course visualy they can see how the food looks on the picture.

## Features

* Used a simple user registration, the password is encrypted using generate_password_hash function from Werkzeug Security module.
* User can login and is able to create edit, delete his own recipe.
* List all recipes created by the user, with the option to edit or delete the recipe.
* Getting flash mesagges once the recipe is added, updated or deleted.
* Carousel used with pictures and external links which direct the user to a full recipe ingredients and directions of cooking.
* Able to see the most viewed recipes.

## Technologies

* Python3
 
* HTML5
* CSS /Materialize
* JS / JQuery
* Mongo
* Flask

## Testing

* I have been doing testing manualy and everything is working as expected , everything is functional and app runing without errors.
  When i click on home page i can see pictures and recipes, im able to add, edit or delete recipe.
  If an admin login in they can see recipes they can add recipes, edit them or delete them, also they can add categories.
  So all CRUD funcionality is working as expected.

* I used W3C Markup Validator for testing.
  All the pages passing without errors.



## Deployment
The project is hosted on Heroku. For it to run correctly the following is required:

A Procfile that instructs Heroku how to run the app.

requirements.txt. This file informs Heroku what dependencies are required to run the app correctly. It is created by typing on the terminal pip freeze > requirements.txt.

Create a new app in Heroku

Setup in Heroku the environment variables required to successfully run the app in Settings, Config Vars.

* MONGO_DBNAME
* MONGO_URI
* SECRET_KEY
* PORT
* IP

Connect Heroku to the project's repository on Github and setup automatic deployment. Heroku then will build a new version of the app every time a new deployment is pushed to Github.


Happy coding!
