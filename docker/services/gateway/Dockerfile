FROM nginx:alpine


RUN rm /etc/nginx/conf.d/default.conf

COPY resources/* /usr/share/nginx/html

WORKDIR /etc/nginx

EXPOSE 80 443

CMD ["nginx", "-g", "daemon off;"]