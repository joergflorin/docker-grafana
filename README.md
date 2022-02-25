# docker-grafana

Docker service definitions for Grafana server.

Create a following subdirectories in directory `grafana` for storing config data:

```
grafana/data
sudo chown 472:472 grafana/data
grafana/etc
sudo chown 472:472 grafana/etc
grafana/provisioning
sudo chown 472:472 grafana/provisioning
```

Run following command in this directory: 

```
docker-compose up -d
```
