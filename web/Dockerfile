FROM nginx
RUN rm -rf index.html /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY Roboshop.conf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/
