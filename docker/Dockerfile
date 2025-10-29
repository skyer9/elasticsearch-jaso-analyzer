FROM docker.elastic.co/elasticsearch/elasticsearch:9.2.0

COPY jaso-analyzer-plugin-9.2.0-plugin.zip /tmp/
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install file:///tmp/jaso-analyzer-plugin-9.2.0-plugin.zip