# ChirpStack v4 with docker compose

### Docker instalation:
```shell
wget -O get-docker.sh https://get.docker.com
sudo sh get-docker.sh
```

### Run server:
```shell
sudo docker compose up
```

### Server ports:
* 8080 - chirpstack web-interface
* 8090 - chirpstack-rest-api
* 1700 - Semtech UDP Packet Forwarder
* 3001 - basicstation to a LoRaWAN Network Server (LNS) 8 channels
* 3011 - basicstation to a LoRaWAN Network Server (LNS) 16 channels