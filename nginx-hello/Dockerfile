FROM nginx:mainline-alpine
RUN rm /etc/nginx/conf.d/*
ADD ./nginx-demos/nginx-hello/hello.conf /etc/nginx/conf.d/
ADD ./nginx-demos/nginx-hello/index.html /usr/share/nginx/html/
