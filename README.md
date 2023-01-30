```shell
docker build -t geoserver .
```

Afterwards you can run the pulled image locally with:

```shell
docker run -it -p 8080:8080 geoserver
```

Or if you want to start the container daemonized, use e.g.:

```shell
docker run -d -p 80:8080 geoserver
```
Postgis conection
configure HOST replace localhost with

```shell
host.docker.internal 
```