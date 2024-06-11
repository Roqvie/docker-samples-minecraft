# Compose files for creating docker images of minecraft server

[Used project](https://docker-minecraft-server.readthedocs.io/en/latest/)

## Install

### Docker
Ubuntu - Use official [documentation](https://docs.docker.com/engine/install/ubuntu/)

### MC Server
```bash
git clone 
mkdir minecraft & mv docker-samples-minecraft/<TYPE>/docker-compose.yml minecraft/docker-compose.yml
cd minecraft
# Edit config 
nano docker-compose.yml
docker compose up -d
```
*also do not forget to open ports 25565, etc. in the server ufw or provider’s console/app

## Running
```bash
# See list of containers
docker ps -a
# Delete container 
docker rm <CONTAINER ID or NAME> 
# Restart container
docker restart <CONTAINER ID or NAME> 
```

## Console 