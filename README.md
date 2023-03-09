# api-template

<h3>Laravel API based template for backend with admin panel</h3>

## What is it
This is a starter kit for your next API using Laravel, implemented with more than one structure, all battle-tested with the same features listed below.

## Feature

- Admin Panel (using <a href="https://adminlte.io">AdminLTE-3</a>)
- Passport for OAuth2
- migration of user
- curd of user with token (Coming Soon)
- Login 
- Register
- Login with google (Coming Soon)
- Register with google (Coming Soon)
- Password Reset (Coming Soon)

## Setup Project
Clone the repo(https)
```
git clone https://github.com/Tejas20002/api-template.git
cd api-template
```
Clone the repo(ssh)
```
git clone git@github.com:Tejas20002/api-template.git
cd api-template
```
Composer install for vendor folder
```
composer install
```

Run the command to install adminlte 3 file
``` 
npm install 
```
Initialize adminlte in project
```
php artisan adminlte:install
composer require laravel/ui
php artisan ui bootstrap --auth
php artisan adminlte:install --only=auth_views
```
Adminlte 3 Auth Views Customization
```
php artisan adminlte:install --only=main_views
```
for more details use this repo <a href="https://github.com/jeroennoten/Laravel-AdminLTE">AdminLTE-3</a>
