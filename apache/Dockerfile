FROM debian
RUN apt update && apt install -y apache2

EXPOSE 80
EXPOSE 443

WORKDIR /etc/apache2

#CMD tail -f /dev/null
CMD apachectl -D FOREGROUND


