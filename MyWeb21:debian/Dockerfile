# Web server apache2
# debian detach

FROM debian
LABEL subject="webserver"
LABEl author="Dan"
RUN apt-get update && apt-get -y install apache2 iputils-ping iproute2 nmap procps
COPY index.html /var/www/html
WORKDIR /tmp
CMD apachectl -k start -X
EXPOSE 80
