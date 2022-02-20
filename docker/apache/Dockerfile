FROM httpd:alpine3.15

RUN apk update \
    && apk add curl

COPY index.html /usr/local/apache2/htdocs/
