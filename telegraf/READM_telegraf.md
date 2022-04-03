# telegraf

```bash
mkdir --verbose telegraf
docker pull telegraf:1.22.0
docker run --rm telegraf:1.22.0 telegraf config | tee ./telegraf/telegraf.sample.conf
```
