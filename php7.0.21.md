# PHP 7.0.21
Upgrade a PHP workspace to version 7.0.21 in Cloud 9


```
$ sudo add-apt-repository ppa:ondrej/php -y
$ sudo apt-get update -y

$ sudo apt-get install php7.0-curl php7.0-cli php7.0-dev php7.0-gd php7.0-intl php7.0-mcrypt php7.0-json php7.0-mysql php7.0-opcache php7.0-bcmath php7.0-mbstring php7.0-soap php7.0-xml php7.0-zip -y

$ sudo mv /etc/apache2/envvars /etc/apache2/envvars.bak
$ sudo apt-get remove libapache2-mod-php5 -y
$ sudo apt-get install libapache2-mod-php7.0 -y
$ sudo cp /etc/apache2/envvars.bak /etc/apache2/envvars

$ php -v
PHP 7.0.21-1~ubuntu14.04.1+deb.sury.org+1 (cli) (built: Jul  6 2017 09:38:10) ( NTS )
Copyright (c) 1997-2017 The PHP Group
Zend Engine v3.0.0, Copyright (c) 1998-2017 Zend Technologies
    with Zend OPcache v7.0.21-1~ubuntu14.04.1+deb.sury.org+1, Copyright (c) 1999-2017, by Zend Technologies
```
