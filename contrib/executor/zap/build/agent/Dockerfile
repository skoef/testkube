# syntax=docker/dockerfile:1
FROM owasp/zap2docker-stable:2.12.0
ENV ZAP_HOME /zap
COPY zap /bin/runner
ENTRYPOINT ["/bin/runner"]