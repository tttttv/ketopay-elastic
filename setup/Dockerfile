ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
#FROM docker.elastic.co/elasticsearch/elasticsearch:${ELASTIC_VERSION:-8.15.3}
FROM hub.docker.com/_/elasticsearch:${ELASTIC_VERSION:-8.15.3}

ENTRYPOINT ["/entrypoint.sh"]
