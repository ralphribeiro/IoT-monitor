# IoT-monitor
Pilha IoT docker com mosquitto, influxdb, telegraf e grafana

# Como rodar:
- docker-composer up -d
- docker-compose exec influxdb influx
---- CREATE DATABASE sensors
---- CREATE USER telegraf WITH PASSWORD 'telegraf'
---- GRANT ALL ON sensors TO telegraf
