# ShinSakanami/docker
Collection of Docker Compose files I use in my homelab.

# Utilisation
## Ubuntu
Clone repository:
```bash
git clone https://github.com/ShinSakanami/docker/
```

Launch a container:
```bash
cd docker/container
docker compose up -d
```

Useful commands:
- **docker container ls** : Show currently running containers
- **docker compose up -d --pull always** : Create and start the container of the current directory (update with --pull always)
- **docker compose down** : Stop and remove the container of the current directory
- **docker image prune** : Remove unused images
- **git pull** : Update Docker Compose files

# Homelab

See my scripts and configuration files for my home network and servers at https://github.com/ShinSakanami/homelab
