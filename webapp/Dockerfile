FROM terrama2/terrama2:4.0.8

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
                    postgis \
                    # PostgreSQL Client
                    postgresql-client

EXPOSE 36000

COPY docker-entrypoint.sh /

ENTRYPOINT /docker-entrypoint.sh
