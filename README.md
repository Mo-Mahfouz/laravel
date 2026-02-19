# laravel

### how to create new laravel project 
Select path: prefered in 
```
C:\xampp\htdocs
```
then open cmd.... then type 
```
laravel new example-app
```
Run a localHost server For your laravel project (open terminal into your project folder) using this command  
```
php artisan serve
```
also you can run a server for your php file using apache and type it's path after xampp on google ex..
```
localhost/htdocs/index.php
```
**Hint:** We can type index.php or not

To create controler from cmd we use at project folder we use: 
```
php artisan make:controler
```
We should create namespace into the class to use the same path in the php file
namespacing :
```
namespace App\Http\Controllers;
```
include = :
```
use  App\Http\Controllers\TestController;
```
### To understand the construction of the code we should know Design pattern and MVC pattern
this is a good website to learn design pattern
```
http://refactoring.guru/
```
MVC -> Model, View and Controller pattern

Model: Database         -> act with Databases
View: HTML,CSS,JavaScript   
Controller: Simple Logic Classes   -> Get request , give response (First thing interacts with user)
##You can read the evolution of mvc
###You can benifit from dev.to (a website have millions of technical articles)
```
dev.to
```
##CRUD  -> Create , Remove , Update , Delete 
this is the 4 basic operation that happens in any resource at any system

###We can find all project code at the following Link
```
https://github.com/amaelftah/codezilla-blog
```
##Steps to build new Route
1- Define a new Route so the user can access it from browser
2- Define Controller that renders a view
3- Define view that contains list of posts
4- Remove any static HTML data from the view

##Look we can use this to print and terminate the program 
```php
@dd(Variable_name)
```
