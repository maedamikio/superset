# Superset
This Superset works one container

# Docker Hub
This version is 0.20.6

```
$ docker run -d -p 8088:8088 --name superset maedamikio/superset
```

# docker build

```
$ git clone git@github.com:maedamikio/superset.git
$ cd superset
$ docker build -t superset .
```

# docker run 

```
$ docker run -d -p 8088:8088 --name superset superset
```

# Sign In

```
http://localhost:8088/
Username: admin
Password: admin
```

# docker rm

```
$ docker rm -f superset
```
