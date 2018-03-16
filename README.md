# An ELK stack using docker-compose

A simple Elasticsearch, Logstash and Kibana stack which is run on a single node using docker-compose. Simply configure your servers to point to the host IP an either 514/UDP or TCP. Wait a few mins for Kibana to stabilise and then browse to https://host.com to go the Kibana dashboard.

On the 'configure an index pattern', remove logstash-* and put in a single * then press return. In 'time-field name' window at the bottom select whatever is in there and then click create, then the green star at the top and then 'Disover' to see your data!

docker-compose up --remove-orphans -d
