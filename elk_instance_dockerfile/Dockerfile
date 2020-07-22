FROM elasticsearch:7.7.0 
#

VOLUME ["/data"]


ADD config/elasticsearch.yml /elasticsearch/config/elasticsearch.yml
WORKDIR /data
CMD ["/elasticsearch/bin/elasticsearch"]

#  - 9200: HTTP
#  - 9300: transport
EXPOSE 9200
EXPOSE 9300



