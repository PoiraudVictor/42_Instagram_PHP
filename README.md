# 42_Instagram_PHP
Building an Instagram like web app in PHP is the 6th project of 42 cursus (admitting you are in the web branch of the cursus). I have implemented, with bare hands (frameworks are forbidden), the basic functionalities found on most sites with a user base.

I also learned a lot about :
* Responsive design
* DOM Manipulation
* SQL Debugging
* Cross Site Request Forgery
* Cross Origin Resource Sharing

### Build with
* PHP
* Javascript
* MySQL
* HTML/CSS

## Get it

### Prerequisites
You need to have installed [PHP](http://www.php.net/), [MySQL](https://www.mysql.com/fr/) and a local web server of your choice ([MAMP](https://bitnami.com/stack/mamp/installer), [WAMP](https://bitnami.com/stack/wamp/installer), [LAMP](https://bitnami.com/stack/lamp/installer))

### Modify the config file
*config/database.php* contains all the information needed by [MySQL](https://www.mysql.com/fr/) to connect the web app to its database. Modify it so it matches your MySQL config.
```
$DB_DSN = 'mysql:host=127.0.0.1;dbname=insta42';
$DB_USER = 'root';
$DB_PASSWORD = "[Password entered during MAMP/WAMP/LAMP installation]";
```
### Launch the server
Start the server you have installed.

## Get started
1. In phpMyAdmin, add a db called `insta42`
2. In console, run `php config/setup.php`
3. Go to the path `localhost:[yourPort]` in your web browser
4. Have fun

### Screenshots

