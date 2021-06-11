FROM nginx:1.21.0

RUN set -ex; \
    apt-get update; \
    apt-get install -y --no-install-recommends \
    vim;

ADD ./default.conf /etc/nginx/conf.d/default.conf

RUN mkdir -p /var/www/html
WORKDIR /var/www/html
    