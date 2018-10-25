# Superset
- This [Superset](https://superset.incubator.apache.org/) works one container.


# docker run
- You can run container from Docker Hub or Build Image.

## from Docker Hub
- This version is 0.28.1

```shell
$ docker run -d -p 8088:8088 --name superset maedamikio/superset
```

## from Build Image
- You can use the latest Superset!

```shell
$ git clone git@github.com:maedamikio/superset.git
$ cd superset
$ docker build -t superset .
$ docker run -d -p 8088:8088 --name superset superset
```


# Sign In
- http://localhost:8088/
  - Username: admin
  - Password: admin


# Authors
- 前田 幹夫(MAEDA Mikio)
- [Twitter](https://twitter.com/maeda_mikio)
