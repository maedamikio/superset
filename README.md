# Superset

This Superset works one container.

# docker run

You can run container from Docker Hub or Build Image.

## from Docker Hub

This version is 0.20.6

```
$ docker run -d -p 8088:8088 --name superset maedamikio/superset
```

## from Build Image

```
$ git clone git@github.com:maedamikio/superset.git
$ cd superset
$ docker build -t superset .
$ docker run -d -p 8088:8088 --name superset superset
```

# Sign In

```
http://localhost:8088/
Username: admin
Password: admin
```

# Authors

* **MAEDA Mikio** - [Twitter](https://twitter.com/maeda_mikio)
