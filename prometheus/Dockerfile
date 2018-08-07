FROM prom/prometheus

# output from docker container inspect
ENV KAFKA_INSTANCE=<your container IP>
# change if you used a different port #
ENV KAFKA_METRICS_PORT=7071

ENV KAFKA_INSTANCE=172.17.0.4

COPY prometheus.yml /etc/prometheus/prometheus.yml
