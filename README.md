# IoT-monitor
Pilha IoT docker com mosquitto, influxdb, telegraf e grafana

# Como rodar:
- git clone https://github.com/ralphribeiro/IoT-monitor.git
- docker-composer up -d

- docker-compose exec influxdb influx
- 1 CREATE DATABASE sensors
- 2 CREATE USER telegraf WITH PASSWORD 'telegraf'
- 3 GRANT ALL ON sensors TO telegraf
