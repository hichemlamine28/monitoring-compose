This is a poc using docker-compose to deploy grafana, node-exporter, prmetheus, cadvisor, redis 

docker compose up -d # or # docker-compose up -d # depending on installation of docker compose

docker compose down # or # doker compose down --volumes

docker rmi $(docker images -aq)


docker compose ps # to see ports for each service

localhost:3000  # grafana
localhost:9090  # prometheus
localhost:8080  # cadvisor
localhost:9100  # node-exporter


You can import other dashbords via json file or only with ID and try

i Will add loki, promtail on other repos

 !!! Enjoy !!!
                Hichem Elamine




