# Contribuições para o desenvolvimento do GEOCEM
## Start Docker
'''
$ sudo systemctrl start docker
'''
## Start Docker compose
'''
$ docker-compose -f docker-compose.yml up -d
'''

## Enter to the bash of the container
'''
$ docker exec -it django4geonode /bin/bash
'''
## Once logged in the GeoNode image, follow the logs by executing
'''
$ tail -F -n 300 /var/log/geonode.log
'''
## Stop the container
'''
$ docker-compose stop
'''


