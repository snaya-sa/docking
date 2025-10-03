FROM ghcr.io/shipsaas/docking:latest

RUN apt-get update && apt-get install -y libpq-dev

RUN docker-php-ext-install pdo_pgsql pgsql

ENTRYPOINT ["/entrypoint"]
