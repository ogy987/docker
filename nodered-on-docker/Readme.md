# NodeRED on docker compose

#start container with command:

docker-compose up

#shut down container with command:

docker-compose down

all settings and flows in NodeRED will be saved in nodered_volume that is configured in docker-compose.yml file
command to check docker volumes:
docker volume ls
location of nodered_volume in linux:
cd /var/lib/docker/volume/
