
# Deployment manifests to collect container's logs using EFK stask (Elasticsearch , Filebeat and Kibana)

## How to use :
 Markup : * docker-compose up
          * go to http://localhost:5601/
          * Create index pattern with filebeat-* as a idex name and @timestamp as a time filter
          * go to discover and all your containers ' logs can be found there 

