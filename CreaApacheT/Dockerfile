FROM debian:latest

RUN apt-get update && apt-get install -y apache2 

RUN /usr/sbin/a2ensite default-ssl
RUN /usr/sbin/a2enmod ssl

EXPOSE 80 443

CMD /usr/sbin/apache2ctl -DFOREGROUND
