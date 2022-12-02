FROM debian
RUN apt update && apt install -y apache2 php libapache2-mod-php php-zip php-mbstring php-cli php-common php-curl php-xml php-mysql

EXPOSE 80
EXPOSE 443

WORKDIR /etc/apache2

#CMD tail -f /dev/null
CMD apachectl -D FOREGROUND


