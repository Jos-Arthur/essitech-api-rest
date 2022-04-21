# essitech-rest-api-crud

- essitech-rest-api-crud # This project allows you to manage all transactions related to the creation of products and users.

- php artisan route:list # This command lists all the routes and their details.

For the documentation of our APIs we used Swagger.

- composer require "darkaonline/l5-swagger"

- open your config/app.php and add this line: L5Swagger\L5SwaggerServiceProvider::class

- php artisan vendor:publish --provider "L5Swagger\L5SwaggerServiceProvider"

- php artisan l5-swagger:generate #This command allow to generate documentation

- Connect Database.

- Run php artisan migrate:fresh --seed


