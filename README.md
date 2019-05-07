# Recipe Website (Developed in a team of four 1.Naveen Kusakula 2.Suresh Kumar Gangumalla 3.Sai Chand Singamaneni 4.Navneet Singh )

# Overall Concept

This project will be a full stack website that allows the public to sign up, log in, and then post and search for and cooking recipes.  It will have the following features:
	
# Two types of users:
# Administrator:
	The site will have one administrator that logs in with the username “admin” with a password set by environmental configuration (not hardcoded).
	The administrator shall have the ability to approve recipes to be posted to the website.
# Regular User:
	Regular users register for the site by entering in their details and passwords.  They log into the site via email and password stored in the database.  Passwords are salted in the database.
	They can browse the site, or search the site for recipes.
	When logged in the users can post new recipes
	When logged in, they rate recipes on recipes.
	They can follow other users, and get notified when the other user post new recipes.
The main purpose of the site is to find (by browsing or searching) and rate recipes:
	All of the details for the recipes are stored in the database
	Records of ratings of the recipes are stored in the database.
	The database is searchable
	The users can do a simple text search that searches all fields in the database
	The users can also click the search link to go to an advanced search page where they can search by individual fields (content type: cuisine, name, poster, categories: Bread Recipes, Cake Recipes, Chicken Recipes, Pasta and Noodles, Vegan Recipes [a recipe may belong to multiple categories], ingredients, steps and description)
	Users can post recipe by clicking the post button to post a recipe.
	Users can rate recipe items on a star rating of 1 to 5.  
	The user can also follow the poster of other recipes and are notified via email the followed user posts new recipe
	The site must implement the email functionality, send an email to the user with details on the recipe

# Pages

The site must have the following minimum set of pages / behaviour:
# Main page:  
This page lets even non-logged in users browse the recipes, it allows users to login or signup, and also lets users do simple text searching of the database.
# Main page (Administrator mode): 
When logged in as the administrator the main page shows one links to administrator only pages: the approve recipe item page.
# Login page: 
User can log into the system, after logging in successfully they are redirected to the main page.
# Register / signup page:
User can sign up as a new user entering all their details, after signup they are redirected to the main page.
# Administrator approve recipe page:
Through this page administrators can approve recipes to the site.  Once approved the item should show up when browsing or searching the site.
# Item details page: 
This page has all the details of a recipe and provides a way for users other than the writer to rate a recipe from 1 to 5 starts.  Also only for administrator the page allows deletion of recipe.
# Search results page:  
Whether a user does an advanced search, or a simple text search this page lists all recipes that matched their search
# Advanced search page: 
This page allows users to search by specific fields in the database (content type: recipe type, cuisine, name, poster, categories: Bread Recipes, Cake Recipes, Chicken Recipes, Pasta and Noodles, Vegan Recipes [a recipe may belong to multiple categories], ingredients, steps and description)
