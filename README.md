Movie LIBRARY SYSTEM
================

General Info
------------
> Movie Collection is a Spring Boot Web Application using Spring Boot, Maven, JPA/Hibernate, Thymeleaf, Bootstrap, Spring Security, MYSQL Database.

### Features
* Add movies to the collection or Delete / Update movies from the collection.
* View movie entries (Name, Release Date, Description, Image, Rating, Cast)
* Login / Register to have access to viewing the collection or managing it.
* Authorization system, meaning that you have to be the admin to add/update/delete movies but viewing is accessable via a user role.

### How To Use
> #### What You Need
> Make sure port 8080 isn't in use.
* Download the files and make sure they're inside a folder. (Name can be anything)
#### TO RUN WITH AN IDE
> * On SpringToolSuite4 (or Eclipse or Intellij), File -> Import -> Existing Maven Projects -> Choose the folder
> * When importing process is done, right-click on the root directory (from Package Explorer) Run As -> Spring Boot Application


* Before running application I need to intruct you that create and admin by defaulty by adding ROLE -> 'ROLE_ADMIN' in Database... I did not do some admin assignment selection where we need to have only one admin right......
* Once the app runs, open your browser and type http://localhost:8080 as the url. You'll get redirected to the login page.
* You can register, then login. There are already two registered accounts in the app.

* ****NOTE****
* I provided data.sql and schema.sql to create a schema and data to be inserted using sql queries do query those ...
* DataBase Integration :
* After creating schema -> Go to application.proprties -> update the username and password of particular db
******* RUN THE APP.....