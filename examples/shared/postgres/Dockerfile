FROM postgres:latest@sha256:f7039b454d9dcb8796bada8390e94ff09f89bfdfcfd7e134bd28e3de672dd5e6
COPY docker-healthcheck.sh /usr/local/bin/
HEALTHCHECK CMD ["docker-healthcheck.sh"]
