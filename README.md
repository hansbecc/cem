# Contribuições para o desenvolvimento do GEOCEM
### Start Docker
```bash
$ sudo systemctl start docker
```
### Start Docker compose
```bash
$ docker-compose -f docker-compose.yml up -d
```

### Enter to the bash of the container
```bash
$ docker exec -it django4geonode /bin/bash
```
### Once logged in the GeoNode image, follow the logs by executing
```
$ tail -F -n 300 /var/log/geonode.log
```
### Stop the container
```
$ docker-compose stop
```
### To see the IPAdress of the container with ID_X
```bash
$ docker inspect ID_X | grep IPAddress.
$ telnet ip_x port_x
```
