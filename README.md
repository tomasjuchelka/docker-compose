# docker-compose

Running docker-compose from a container:

```sh
docker run --rm -v /var/run/docker.sock:/var/run/docker.sock -v "$PWD:$PWD" -w="$PWD" linuxserver/docker-compose up -d
```

Or using pip3 install:

```sh
sudo apt-get install libffi-dev libssl-dev
sudo apt install python3-dev
sudo apt-get install -y python3 python3-pip
sudo pip3 install docker-compose
```
