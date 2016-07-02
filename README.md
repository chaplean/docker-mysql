Docker MySQL image
=====================

From mysql image

## Build image

```
docker build -t chaplean/mysql .
```

## Push image (Public Cloud)

You need to make `docker login` first

```
docker tag chaplean/mysql chaplean/mysql:latest
docker push chaplean/mysql
```
