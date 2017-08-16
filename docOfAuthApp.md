# this  docmantation  for  authapp
#1- create  the  project  'composer  create-project laravel/laravel=4.2.0 authapp --prefer-dist'
#2- go  to  make  the database through migrate ' php  artisan migrate:make create_users'
#3- then  fill  the the  user table  
#4- then go  to  make  sesstion to  make  user  logedin  in every page in the commend ' php          artisan   session:table'
#5-  then  migrate  the database'php artisan migrate'
#6- need to  install  faker  to insert  a fake data  ''
#7-to use  Form  in  html {{Form::}} you  shoud  do some  setpes 
   #1- "Edit your project's composer.json file to require   require": {"laravelcollective/html": "~5.0"}
   #2- Next, update composer from the Terminal: 'composer update'
   #3- Next, add your new provider to the providers array of config/app.php: 'providers' =>           ['Collective\Html\HtmlServiceProvider',],
   #4-Finally, add two class aliases to the aliases array of config/app.php: 'aliases' => [ 'Form' => 'Collective\Html\FormFacade','Html' => 'Collective\Html\HtmlFacade',],





Erros  Section 
#1- if you  have  problem  with input  but  'use Illuminate\Support\Facades\Input;'  in RigisterController 
#1- if you  have  problem  with Hash ues  this  'use Hash;' in RigisterController 