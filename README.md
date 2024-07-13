[AlertManager](http://minis.fritz.box:9093) \
[Prometheus](http://minis.fritz.box:9090) \
[Minis NodeExporter](http://minis.fritz.box:9100)

# Prometheus Homelab Stack

Sourced from [this fine article](https://mxulises.medium.com/simple-prometheus-setup-on-docker-compose-f702d5f98579).

## Start and Stop

* `docker compose up -d --force-recreate`, verify with curl localhost:9090
* `docker compose down`
