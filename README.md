# Mariadb-docker-app

This repository contains a dockerfile to run the mariadb database on your machine.

1 - The only change needed is to update the volume on line 16, this part "~/projects/database/mariadb/db", to your project path.

2 - Then run the docker compose command below, to download the mariadb image, and also run the container.

```
docker compose up
```
Ready :)
