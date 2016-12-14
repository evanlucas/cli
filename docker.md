## docker

### Remove all containers

```shell
$ docker ps -aq | xargs docker rm -f
```

### Remove all volumes

```shell
$ docker volume ls -q | xargs docker volume rm
```
