# k6-boilerplate

### How to run the project:
```
docker-compose up -d influxdb grafana
docker-compose run k6 run /scripts/test.js
```