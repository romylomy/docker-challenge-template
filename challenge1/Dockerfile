FROM nginx
RUN  apt-get -y update && apt-get -y install nginx
COPY public/default /etc/nginx/sites-available/default
COPY public/index.html /usr/share/nginx/html/index.html
EXPOSE 80
