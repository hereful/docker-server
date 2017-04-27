FROM eboraas/laravel
MAINTAINER Alex Hsieh <notlose@hotmail.com>

RUN apt-get update && apt-get -y install php5-curl php5-gd && apt-get -y autoremove && apt-get clean && rm -rf /var/lib/apt/lists/*

EXPOSE 80
EXPOSE 443

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]