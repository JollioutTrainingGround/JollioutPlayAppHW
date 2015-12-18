# JollioutPlayAppHW

##Introduction

This repository is your training ground.

Here you will be able to learn how to use git as a version
controll system, as well as most importantly, how to use
the play framework to create a simple web app.

##Tasks

* Create your own branch for the repository
    * Here is a link that will help you with this: https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging

* Download and install Activator
    * https://www.playframework.com/documentation/2.3.x/Installing

* Create an application which implements a basic authentication process.


##Authentication.

###Views
Views are used to implement html pages. The only thing you have to do here
is to create a simple index page which will accommodate the Form used for 
the authentication.

###Controllers
Controllers are used to controll the application, they are the ones who make POST and
GET requests and communicate with the Front End (the Views).

###Entities
Entities will be used to represent entities of the application and get Data from the
Html Forms.

###Models
Models are used to create our database schema. In our case we are going to only create one class
in this packet, the user.

###Bonus 1 
Create an active session for the authenticated customer, and display his data after his authentication.

###Bonus 2 
Create a "real" Database, using mysql.

##Conf Directory
The conf Directory has the routes file, which is used to determine the 
routes for POST and GET request, for example
GET     /index                       controllers.Application.index()
renders the index page when the URL is jolliout.com/index.

##Study Material

https://www.playframework.com/documentation/2.1.1/JavaGuide4

https://www.playframework.com/documentation/2.1.0/JavaForms

https://www.playframework.com/documentation/2.0/JavaEbean

https://www.playframework.com/documentation/2.0/JavaRouting

##Notes

Ebean comes installed with play framework, however it is not configured, but the tutorial has more than enough
documentation to help you configure it.

###Merry Christmas!!!!
