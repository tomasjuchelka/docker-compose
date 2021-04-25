# docker-compose

Running docker-compose from a container, because it can't be installed on armv7 arch (or I'm not able to make it working :)).

```sh
docker run --rm -v /var/run/docker.sock:/var/run/docker.sock -v "$PWD:$PWD" -w="$PWD" linuxserver/docker-compose up -d
```
