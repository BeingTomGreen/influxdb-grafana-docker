## InfluxDB & Grafana in Docker

**WIP**

### TIPz

Download the latest Gafana config file for your version:

docker run --rm --entrypoint /bin/bash grafana/grafana:latest -c 'cat $GF_PATHS_CONFIG' > ./provisioning/grafana/grafana.ini

Download the latest Gafana config file for your version:

docker run --rm influxdb:latest influxd print-config > ./provisioning/influxdb/config.yml