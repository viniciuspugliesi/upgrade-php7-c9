# PHP 7.1.13
Upgrade a PHP workspace to version 7.1.13 in Cloud 9


```
sudo add-apt-repository ppa:ondrej/php -y
sudo apt-get update -y
 
sudo apt-get install php7.1-curl php7.1-cli php7.1-dev php7.1-gd php7.1-intl php7.1-mcrypt php7.1-json php7.1-mysql php7.1-opcache php7.1-bcmath php7.1-mbstring php7.1-soap php7.1-xml php7.1-zip -y
 
sudo mv /etc/apache2/envvars /etc/apache2/envvars.bak
sudo apt-get remove libapache2-mod-php5 -y
sudo apt-get install libapache2-mod-php7.1 -y
sudo cp /etc/apache2/envvars.bak /etc/apache2/envvars
 
sudo a2dismod php5
sudo a2enmod php7.1
 
sudo service apache2


$ php -v
PHP 7.1.13-1+ubuntu14.04.1+deb.sury.org+1 (cli) (built: Jan 16 2018 15:37:12) ( NTS )
Copyright (c) 1997-2017 The PHP Group
Zend Engine v3.1.0, Copyright (c) 1998-2017 Zend Technologies
    with Zend OPcache v7.1.13-1+ubuntu14.04.1+deb.sury.org+1, Copyright (c) 1999-2017, by Zend Technologies
```
