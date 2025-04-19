# keycloak-psql-pgadmin
run docker images of keycloak with psql along with pgadmin

Steps:

- docker pull postgres:latest
- docker pull dpage/pgadmin4:latest
- docker pull quay.io/keycloak/keycloak:latest
- git clone https://github.com/vgupta23/keycloak-psql-pgadmin
- docker-compose up -d
- pgadmin url:http://localhost:8888/login?next=/
- keycloak url:http://localhost:8080/


