
# Balkan Flavours 

![Recipe cookbook Project](/static/images/am-i-responsive.png)

 As a food lover I want to share with the world Balkan cuisine. This project is created to give the users information about the Balkan Cuisine and share with them most popular recipes. I think the users will have the opportunity to learn new recipes from different countries.

# Contents:

* UX
* Project Goals
* Target Audience Goals
* Site Owner Goals
* User Stories
* User Requirements and Expectations
* Images
* Wireframes
* Testing
* Bugs
* Static files
* Deployment
  
## Features

* Features that have been developed
* Technologies Used
* Planning + Testing:
* Bugs
* Deployment
  
# UX (User Experience)

## Project Goals
* The main goal for this project is to share some delicious recipes from Balkan cuisine.
* The project is created for all people who have interest on cooking and want to explore more ways on preparing their meals.
* The website needs to be attractive and interactive providing an good User Experience to everyone who will use this site.
* I want to offer access for the users to register and be part of this site by sharing their own recipes.
* For making this project functional i put into practice the skills learned during the course.

## User Goals:

* A website that provides a good experience.
* Visual interaction is important to give the idea how the food looks after preparetion.
* To have access on the website by registering and login.
* Having all the details needed for a recipe such as ingredients and directions.
* Adding own recipes and save, update and delete them.
* A website that works on mobile , tablet , desktop.

## User Stories:

* Inna: " As a user i want to learn about different countries cuisine."
* Adela M : " When i visit such sites i want to be able to register, login and share my recipes with other users."
* Tom : " I want to navigate and get information about tradicional food in Balkan. "
* Arion : "When i share my recipes i would like to have full access on my recipes so i can update or delete if is needed"

## Site Owner Goals:

* Make interactive website and get the users enjoy their navigation.
* Make it easy for the users to navigate, find information and details for each recipe.
* Offer different categories of recipes and different countries traditional food.
* Visually pleasing and a good description of the recipes.

## User Requirements and Expectations:

* Requirements:
  *  Use an interactive website and find interesting recipes.
  * Provide information of the recipes in details to make it easy to understand.
  * Need to see images of different food..
  * To be able to share and save my recipes on this site.

* Expectations:
  * When you click on a recipe to provide all important details such as ingredients and directions.
  * When adding own recipe to be able to save them on this site .
  * Content to be informative and visually pleasing.
  * Receive flashing messages for all the actions taken by the user .

## Images:
* I used images from google for this project.

## Wireframes:
 * Created a simple wireframes by using [Balsamiq](https://chrome.google.com/webstore/detail/balsamiq-wireframes-free/imbfadckkgblfbkinjejdeobpfbcopgb)
 * I saved my wireframes as [PDF](https://acrobat.adobe.com/ie/en/acrobat/features.html?mv=search&sdid=QTV3P4CL&ef_id=121a635018a0184689a703e432189a83:G:s&s_kwcid=AL!3085!10!78890085992494!78890351607325&msclkid=121a635018a0184689a703e432189a83)
* My wireframes :

    * [Phone wireframe](/workspace/Balkan-Flavours/static/images/wireframes/phone.png)
    * [Tablet wireframe](/workspace/Balkan-Flavours/static/images/wireframes/tablet.png)
    * [Browser wireframe](/workspace/Balkan-Flavours/static/images/wireframes/desktop.png)

## Features

* Used a simple user registration, the password is encrypted using generate_password_hash function from [Werkzeug](https://pypi.org/project/Werkzeug/) Security module by using (pip install -U Werkzeug) command.
* Used [Mongodb](https://cloud.mongodb.com/)  document database to host all the data of my site such as recipes, usernames ect.
* User can login and is able to create edit, delete his own recipe.
* Created an admin for the site giving access to add more categories, update or delete categories. If You like to login as an admin
  here you have admin credentials (*__username : admin__*), (*__password : Lalushi1__*)
* List all recipes created by the user, with the option to edit or delete the recipe.
* Getting flash mesagges once the recipe/category is added, updated and getting confirmation prompts when trying to delete a recipe/category.
* Carousel used with pictures of new recipes.


# Technologies Used

## Languages:
* [Python3](https://www.python.org/)
* [HTML5](https://html.com/)
* [CSS /Materialize](https://materializecss.com/)
* [JS / JQuery](https://jquery.com/)
* [Mongodb](https://cloud.mongodb.com/)
* [Flask](https://flask.palletsprojects.com/)
  
## Tools and Libraries:

* [Git](https://git-scm.com/)
* [Bootstrap](https://maps.google.com/)
* [Jquery](https://jquery.com/)
* [Font-Awesome](https://fontawesome.com/)
* [TinyPng](https://tinypng.com/) __(image compression)__
* [Am-I-Responsive](http://ami.responsivedesign.is/)
* [W3-Official-Validator](https://validator.w3.org/)
* [Heroku](https://dashboard.heroku.com/)
* [MongoDb](https://www.mongodb.com/)
* [Materialize](https://materializecss.com/)
* [Pep8](https://pep8.org/)

## Testing

* I have been doing testing manualy and everything is working as expected , everything is functional and app runing without errors.
* When testing i need to check every page and their functionality.
* When i click on [home page](/static/images/home-page.png) i can see pictures and recipes, 
* im able to [add](/static/images/added-recipe.png) recipe, 
* [edit](/static/images/edit-page.png) recipe or [delete](/static/images/delete-page.png) recipe.
* As a user im able to [register](/static/images/registration-page.png) and log in and see a [profile](/static/images/profile-page.png) page
* If an admin [login](/static/images/home-page.png) in they can see recipes they can [add](/static/images/added-recipe.png) recipes,
*  [edit](/static/images/edit-page.png) them or [delete](/static/images/delete-page.png) them, also they can add categories.
*  And the user can successfully [logout](/static/images/logout-page.png).
  So all CRUD funcionality is working as expected.

* I also used DevTools to check if is any error on my website, and everything is working as expected without errors.

* I used W3C Markup Validator for testing.
* First step is by copping the URL of my project and check it if is any error.
  All the pages passing without errors.
* [Login-page](/static/images/w3c-login-page.png) passing without errors.
* [Register-page](/static/images/w3c-register-page.png) no errors found.
* [Add-recipe-page](/static/images/w3c-add.png) passing without errors.

* Manualy tested python code through [PEP8](http://pep8online.com/) passing withot errors.
  [pep8 checker](/static/images/pep8.png)

## Deployment
The project is hosted on Heroku. For it to run correctly the following is required:

* A Procfile that instructions Heroku how to run the app.
  To run this site use *__python app.py__*
* requirements.txt. This file informs Heroku what dependencies are required to run the app correctly. It is created by typing on the terminal pip freeze > requirements.txt.

* Create a new app in Heroku

* Setup in Heroku the environment variables required to successfully run the app in Settings, Config Vars.

  * MONGO_DBNAME
  * MONGO_URI
  * SECRET_KEY
  * PORT
  * IP

Connect Heroku to the project's repository on Github and setup automatic deployment. Heroku then will build a new version of the app every time a new deployment is pushed to Github.

[Deployment on Heroku]( https://flask-balkan-flavors-project.herokuapp.com/)


Happy coding!
