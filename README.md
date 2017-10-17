# docker-postgres

`sudo docker rm -f postres ; sudo docker run -d --name postgres -e POSTGRES_PASSWORD=pass -v postgres:/var/lib/postgresql/data --network my-bridge postgres:10-alpine`
