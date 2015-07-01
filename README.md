# docker-consul

Simple simple simple docker container for consul

Expects to have a directory for configs mounted into `/config` and for data into `/data`.

WebUI ends up living in `/webui`

Recommended run command:

```
docker run -v $CONFIG_DIR:/config -v $DATA_DIR:/data -p 8300:8300 -p 8301:8301 -p 8302:8302 -p 8400:8400 -p 8500:8500 -h $HOSTNAME sjoeboo/consul
```
