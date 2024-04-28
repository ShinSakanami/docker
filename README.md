# docker
Collection of Docker Compose files I use in my homelab.

# Utilisation
## Ubuntu
Clone repository:
```bash
git clone https://github.com/ShinSakanami/docker/
```

Launch a service:
```bash
cd docker/service
docker compose up -d
```

Useful commands:
- **docker container ls** : Show current Docker containers
- **docker compose up -d** : Launch the service of the current directory
- **docker compose stop** : Stop the service of the current directory
- **git pull** : Update files from the repository (use it in docker directory)