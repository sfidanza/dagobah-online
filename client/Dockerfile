FROM nginx:1.28.0-alpine

WORKDIR /var/www/dagobah-online

RUN rm /etc/nginx/conf.d/default.conf
COPY sites-available/dagobah-online.conf /etc/nginx/conf.d/

COPY ./src .