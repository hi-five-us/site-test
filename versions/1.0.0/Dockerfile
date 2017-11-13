FROM nginx:alpine

# nginx confs
COPY conf/etc/nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf
COPY conf/etc/nginx/conf.d/site.test.conf /etc/nginx/conf.d/site.test.conf

# static content
COPY conf/var/www/site.test/html /var/www/site.test/html

# Volumes - optional usage
VOLUME /etc/nginx/conf.d
VOLUME /var/www/site.test/html
