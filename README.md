Docker MySQL image
=====================

From `mariadb:10.1` image

## Build image

```
docker build -t chaplean/mysql .
```

## Push image (Public Cloud)

You need to make `docker login` first

```
docker tag chaplean/mysql chaplean/mysql:VERSION
docker push chaplean/mysql
```
