# fluentd/Dockerfile
FROM fluent/fluentd:v1.17-1
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-force", "--version", "5.2.0"]
