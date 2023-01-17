FROM nginx:1.16
RUN rm /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
COPY image.svg /usr/share/nginx/html/
RUN chmod 444 /usr/share/nginx/html/index.html
RUN chmod 444 /usr/share/nginx/html/image.svg
