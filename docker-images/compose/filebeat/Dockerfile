FROM docker.elastic.co/beats/filebeat:${ELASTICSEARCH_VERSION:-7.9.3}
# Copy our custom configuration file
COPY filebeat.docker.yml /usr/share/filebeat/filebeat.yml
USER root
