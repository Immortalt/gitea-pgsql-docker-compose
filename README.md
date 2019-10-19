# Gitea-Pgsql-Docker-Compose

A Docker Compose file for Gitea - Git with a cup of tea ([gitea.io](https://gitea.io)) with Postgresql Database.

Data will be saved in separate docker volumes to enable easy upgrades!  
Make sure you have the `/mnt/data/` folder.

## Requirements

- docker
- docker-compose

## Getting Started

1. Change Database Password _your_password_ to your own password.

2. Start docker containers (you can also use the Portainer):

```
$ docker-compose up -d
```

After that open gitea installer via browser: [http://localhost:80](http://localhost:80) and fill the form.
