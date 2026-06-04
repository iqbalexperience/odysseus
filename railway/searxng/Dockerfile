FROM searxng/searxng:2026.5.31-7159b8aed

USER root

COPY settings.yml.template /tmp/searxng-settings.yml.template
COPY entrypoint.sh /railway-entrypoint.sh

RUN chmod +x /railway-entrypoint.sh

ENTRYPOINT ["/railway-entrypoint.sh"]