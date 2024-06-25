FROM nginx:latest

WORKDIR /home/

COPY . /home/
COPY www.milansuras.conf /etc/nginx/conf.d/www.milansuras.conf
COPY default.conf   /etc/nginx/conf.d/default.conf

CMD ["nginx", "-g", "daemon off;"]

