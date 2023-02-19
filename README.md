# logstash development environment

This project is mainly to test logstash filters

Write the filter you are wanting to test in logstash/pipeline/logstash.conf

Startup:

`docker-compose up`

test your data using the curl command

`curl -X POST http://localhost:50000 -H 'Content-Type: application/json' -d '{"message":"logging is fun"}'`
