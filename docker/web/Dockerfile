FROM nginx:1.14-alpine

ADD ./site.conf /etc/nginx/conf.d/default.conf
ADD ./uwsgi_params /etc/nginx/uwsgi_params

RUN mkdir -p /app/public
