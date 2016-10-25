# Content Tools Nginx Docker Image - PHP & Nginx
If you want to build a Content Tools application using PHP, this is a base docker image you can use.

### Build
To build this image yourself from the code follow these command
```sh
$ docker build -t whitehart/nginx-php-7 .
```

### Demo Run (If you have a public folder with index.php)
```sh
$ docker run -it -p 8080:80 -v ~/Sites/php-nginx:/var/www/html:rw --rm --name whitehart-php-local whitehart/nginx-php-7
```

License
----
Proprietory
