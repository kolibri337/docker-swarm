# fluentd/Dockerfile

FROM fluent/fluentd:v1.17-1
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-force", "--no-document", "--version", "5.2.0"]
USER fluent
