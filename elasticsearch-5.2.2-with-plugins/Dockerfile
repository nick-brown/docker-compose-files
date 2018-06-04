FROM docker.elastic.co/elasticsearch/elasticsearch:5.2.2

COPY ./firstname-synonyms.txt /usr/share/elasticsearch/config/
COPY ./state-synonyms.txt /usr/share/elasticsearch/config/
RUN elasticsearch-plugin install analysis-phonetic
