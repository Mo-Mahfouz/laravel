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
namespace App\Http\Controllers\TestController;
```
# include = :
```
use  App\Http\Controllers\TestController;
```
