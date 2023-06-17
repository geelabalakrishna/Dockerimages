FROM ubuntu
LABEL mail="balakrishna@gmail.com"
LABEL name="Balakrishna.G"
RUN apt-get update && apt-get install -y nginx net-tools iputils-ping  dnsutils
COPY index.html /usr/share/nginx/html/index.html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
