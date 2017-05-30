FROM debian:latest

RUN apt-get update && apt-get -y install apache2 && apt-get clean && rm -rf /var/lib/apt/lists/*

EXPOSE 80

CMD /usr/bin/apachectl -DFOREGROUND


