FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /usr/nginx/nginx.conf
ADD nginx.conf /etc/nginx/nginx.conf
ADD static/* /usr/share/nginx/html/