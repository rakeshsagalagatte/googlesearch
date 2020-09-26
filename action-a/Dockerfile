FROM debian:9.5-slim
FROM python3.8.2

ADD entryaction.sh /entryaction.sh
RUN chmod +x /entryaction.sh
ENTRYPOINT ["/entryaction.sh"]