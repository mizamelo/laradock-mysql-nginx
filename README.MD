## `LARADOCK` with `MySQL` 

This project contains three images for easy development with Laravel and MySQL. Are they:

1 - Nginx

2 - PHP-fpm

3 - MySQL

4 - PHPMyAdmin

## __How to install__

At your terminal enter the code below to upload the images. 

````bash
$ docker-compose up -d
````

Now enter in the terminal of the image laradock-php-fpm

````bash 
$ docker exec -it laradock-php-fpm /bin/bash
````

Run `composer install` to install the dependencies

````bash 
$ composer install
````

Access your browse at http://localhost:8088 and VUA-LÁ, enjoy! Pay attention, the Laravel's version used is 5.6. For the database, access the url http://localhost:8005 with the user's credentials.


