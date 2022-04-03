# influxdb

```bash
mkdir --verbose influxdb
docker pull influxdb:1.8.10
docker run --rm influxdb:1.8.10 influxdb config | tee ./influxdb/influxdb.sample.conf
```
