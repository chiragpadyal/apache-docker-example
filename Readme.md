# Docker Apache and Mysql

## build image
```
$ docker build -t my-apache2 .
```
## run docker image
``` 
$ docker run -d --name my-running-app -p 8080:80 my-apache2
```
