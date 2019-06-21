ARG ELK_VERSION

From docker.elastic.co/beats/filebeat:${ELK_VERSION}

RUN mkdir -p /usr/share/filebeat/logs

# COPY ./config/filebeat.yml /usr/share/filebeat/config/filebeat.yml
# USER root
# RUN chown root:filebeat /usr/share/filebeat/config/filebeat.yml
# USER filebeat
