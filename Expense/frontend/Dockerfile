FROM nginx
RUN -rf /usr/share/nginx/html/index.html
RUN -rf /etc/nginx/nginx/conf
COPY nginx.conf /etc/nginx/conf
COPY code /usr/share/nginx/html/