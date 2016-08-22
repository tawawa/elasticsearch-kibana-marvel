## Elasticsearch, Kibana, and Marvel in one container

Simple and lightweight docker image for previewing Elasticsearch, Kibana, and Marvel.

### Usage

    docker run -d -p 9200:9200 -p 5601:5601 arcseldon/es-kib-marvel

You can connect to Elasticsearch with `http://localhost:9200` and its Kibana front-end with `http://localhost:5601`.

You can connect to Marvel with `http://localhost:5601/app/marvel`
 

### Tags

* latest

    Elasticsearch-2.3.5 Kibana-4.5.3

* kibana3

    Elasticsearch-1.7.4 Kibana-3.1.3

### Tips

* Install plugins

    `docker exec -u elasticsearch CONTAINER elasticsearch/bin/plugin install PLUGIN_NAME`


