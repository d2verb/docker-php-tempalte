# Docker php template

## Build images
```
$ mkdir laravel_app
$ mkdir app
$ git clone https://github.com/d2verb/docker-php-tempalte docker
$ cd docker
$ docker-compose build
$ docker-compose up -d
```

## Create laravel project
```
$ cd docker
$ docker-compose exec php laravel new
$ ls ../app
README.md         artisan           composer.json     config            package-lock.json phpunit.xml       resources         server.php        tests             webpack.mix.js
app               bootstrap         composer.lock     database          package.json      public            routes            storage           vendor
```
