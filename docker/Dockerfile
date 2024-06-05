FROM docker.elastic.co/elasticsearch/elasticsearch:8.12.1

COPY jaso-analyzer-plugin-8.12.1-plugin.zip /tmp/
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install file:///tmp/jaso-analyzer-plugin-8.12.1-plugin.zip