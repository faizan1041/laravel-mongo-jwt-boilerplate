# laravel-mongo-boilerplate
1. Install Mongodb PHP Extension `sudo apt-get install php-mongodb` or `sudo apt-get install php5-mongo` if using PHP5

2. Run `composer update`

3. Environment settings:
```
DB_CONNECTION=mongodb
DB_HOST=localhost
DB_DATABASE=homestead
DB_USERNAME=homestead
DB_PASSWORD=secret

```
Also make sure to generate the key: `php artisan key:generate`
