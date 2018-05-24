FROM nginx:latest

RUN mkdir nginx_page
COPY ./index.html /nginx_page/index.html
COPY ./nginx.conf /etc/nginx/nginx.conf
CMD ["nginx", "-g", "daemon off;"]