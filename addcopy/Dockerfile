FROM nginx
ADD  https://www.free-css.com/assets/files/free-css-templates/download/page291/hightech.zip /tmp
RUN  apt-get update && apt-get install unzip
RUN  unzip /tmp/hightech.zip
RUN  mv hightech-html/* /usr/share/nginx/html
