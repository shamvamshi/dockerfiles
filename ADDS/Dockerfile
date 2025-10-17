FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/shamvamshi/roboshop-infra-dev/refs/heads/main/60-acm/main.tf /usr/share/nginx/html/index.html