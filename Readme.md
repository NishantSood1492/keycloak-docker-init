1) cp .env.example .env
2) set the env variables
3) run `docker-compose up --build -d`
4) Once the container is up and running
run `docker exec -it keycloak_db psql -U postgres -f /tmp/init.sql`
