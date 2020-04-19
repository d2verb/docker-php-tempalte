# Docker php template

## Prepare
```
$ mkdir project && cd project
$ mkdir app
$ git clone https://github.com/d2verb/docker-php-tempalte docker
```

## Build images
```
$ cd project/docker
$ docker-compose build
```

## Start containers
```
$ cd project/docker
$ docker-compose up -d
```

## Create laravel project
```
$ cd project/docker
$ docker-compose exec php laravel new
$ ls ../app
README.md         artisan           composer.json     config            package-lock.json phpunit.xml       resources         server.php        tests             webpack.mix.js
app               bootstrap         composer.lock     database          package.json      public            routes            storage           vendor
```

You can access to `http://localhost:8080` to check if application works.
