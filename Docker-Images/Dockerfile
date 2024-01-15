FROM ubuntu:latest
LABEL "Author"="Qaderi"
LABEL "Project"="nano"
WORKDIR /usr/share/nginx/html
RUN apt update && apt install nginx -y
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
EXPOSE 8080
ADD nano.tar.gz /var/www/html