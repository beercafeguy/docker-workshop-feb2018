FROM nginx:alpine
COPY default.conf /etc/nginx/conf.d/default.conf
RUN mkdir /usr/share/nginx/html/js
COPY index.html /usr/share/nginx/html/index.html
COPY js/hello_world.js /usr/share/nginx/html/js/
