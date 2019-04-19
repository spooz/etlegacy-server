# etlegacy-server
Enemy Territory Legacy mod server image

### Run:
```
docker run -p 27960:27960/udp --name etlegacy vimes/etlegacy-server
```

#### Docker compose way
copy config/etl_server.cfg.example to etl_server.cfg
```
cp config/etl_server.cfg.example config/etl_server.cfg
```
change passwords and server name adn run
```
docker-compose up -d
``` 

### Dockerhub:
https://cloud.docker.com/repository/docker/vimes/etlegacy-server
