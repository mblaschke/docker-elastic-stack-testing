FROM docker.elastic.co/kibana/kibana:5.4.2

USER root
RUN echo "xpack.security.enabled: false" >> /opt/kibana/config/kibana.yml
USER kibana
