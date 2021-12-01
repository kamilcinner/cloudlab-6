FROM httpd:2.4.35-alpine
RUN apk update && \
    apk upgrade
COPY apache.conf /usr/local/apache2/conf/extend.httpd.conf
RUN echo "Include /usr/local/apache2/conf/extend.httpd.conf" \
    >> /usr/local/apache2/conf/httpd.conf
