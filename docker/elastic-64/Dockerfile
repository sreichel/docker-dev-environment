FROM docker.elastic.co/elasticsearch/elasticsearch:6.4.1

RUN bin/elasticsearch-plugin install analysis-phonetic \
    && bin/elasticsearch-plugin install analysis-icu
