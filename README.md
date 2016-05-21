# alpine-elasticsearch - Alpine based Elasticsearch Container

## Available Tags

* ```2.3.2```,```latest``` (2.3.2/Dockerfile)

## Description
This image contains a compiled version of Elasticsearch installed into Alpine Linux. There is no configuration applied aside from a setting for ES to listen on ```0.0.0.0``` and to utilise the container hostname as the node's name

## Important Ports

* ```tcp/9200``` Elasticsearch default HTTP API port
* ```tcp/9300``` Elasticsearch cluster communication port
