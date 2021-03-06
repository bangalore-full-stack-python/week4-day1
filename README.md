Customer Signup
===============

You've been hired by Time Warner Cable to fix their internal tools-
maybe now they can finally focus on delivering us reliable internet!
Godspeed son, we're all depending on you.

Your task is to build a terminal app that allows their customers to
sign up for service. Once logged in they should be able to create and
update their personal information.

###Requirements

####User

A user should be able to create an account, with only a username and password.

* After they sign up and log in, they should be able to add / update their personal information. A user should have a:
	* first and last name
	* date of birth
	* many phone numbers
	* many addresses.

####Admin

* An admin is just a user but with some extra privleges. An admin can update anybody's information, including their own. 

###Recommendations

* Use sqlite3 and save all the information to a sqlite3 file. You are to write SQL for this challenge. 
	* If you completed the BabyORM assignment you `CANNOT` use it for this assessment. You must write your SQL code from scratch and keep them inside functions/methods.
* Your ERD from the schema designer in question 2 should give you a head start on designing the database.
* It is recommended that you build out all of the user functionality first. 
	* Add admin functionality afterwards. 
	* If your code is extensible, modular and properly object oriented, this should be very easy.
* Make a create file and seed file that will populate your database with Dummy data for you to test the user and admin functionality.
* There should never be any null columns in your database.
* Build this app using the MVC pattern.
