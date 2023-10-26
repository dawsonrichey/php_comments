# PHP Comments

Load comments.sql code into file into database

Create creds.php file

include the following variables and insert your own values
```
$DATABASE_HOST = '';
$DATABASE_USER = '';
$DATABASE_PASS = '';
$DATABASE_NAME = '';
```

Start server
``` 
php -S localhost:8225
```

Force kill the port
```
sudo lsof -t -i:8225
```


Initial source code https://codeshack.io/