# docker-postgres

`sudo docker rm -f postgres ; sudo docker run -d --name postgres -e POSTGRES_PASSWORD=pass -v postgres:/var/lib/postgresql/data --network my-bridge -e TZ=Europe/Prague postgres:10-alpine`
