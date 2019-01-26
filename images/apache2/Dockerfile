FROM ubuntu
LABEL maintainer="ikambarov@yahoo.com"
RUN apt-get update -y && apt-get install apache2 && apt-get install php -y
ENV TEST Ubuntu
EXPOSE 80
CMD ["/usr/sbin/apache2ctl",  "-D",  "FOREGROUND"]

