
# Deployment manifests to collect container's logs using EFK stask (Elasticsearch , Filebeat and Kibana)

## How to use :
 1. docker-compose up
 2.  go to http://localhost:5601/
 3.  Create index pattern with filebeat-* as a idex name and @timestamp as a time filter
 4.  go to discover and all your containers ' logs can be found there 

