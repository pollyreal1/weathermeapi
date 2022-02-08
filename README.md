# Weather me API

## Project setup

Clone this repo and run
```
composer install 
```

### Setup database

1. Create a database on your server enviroment

2. Edit the mysql configuration on your enviroment on **.env** file

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=weathermeapp
DB_USERNAME=root
DB_PASSWORD=
```

3. Then run the migration

```
php artisan migrate
```

4. Then run the project

```
php artisan serve
```


## Made with Laravel
