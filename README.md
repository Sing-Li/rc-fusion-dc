##  docker compose v1 format

####  start mongo

`docker-compose up -d mongo`

Wait for 2 minutes or until you see that replica set has been setup using `docker logs <container-name>`

####  start rocketchat

`docker-compose up -d rocketchat`

The server will be running on the host machines port 3020
