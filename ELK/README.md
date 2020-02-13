This docker compose will instanciate an ELK suite.


## How to run

Create a directory named `es-data` in your home and set its rights:
```
mkdir ${HOME}/.elk && mkdir ${HOME}/.elk/es-data && chown -R 1000:1000 ${HOME}/.elk/es-data
```

Execute the following command on your host:
```
sudo sysctl -w vm.max_map_count=262144
```

Start Docker : 
```
docker-compose up
```

Kibana will be available on URL : http://localhost:5601

The Logstash port will be available on : http://localhost:4560

The APM port will be available on : http://localhost:8200
