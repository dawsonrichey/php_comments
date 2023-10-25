# PHP Comments

load the comments.sql file into your desired database

create a creds.php file

include the following variables and insert your own values

$DATABASE_HOST = '';
$DATABASE_USER = '';
$DATABASE_PASS = '';
$DATABASE_NAME = '';


start up the server
```
php -S localhost:8225
```

if you need to force kill the port
```
sudo lsof -t -i:8225
```


initial source code provided by https://codeshack.io/