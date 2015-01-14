Настройка связки NGINX + PHP-FPM (Dev)
=====================
sudo apt-get install nginx

sudo apt-get install php5-cli php5-common php5-mysql php5-gd php5-fpm php5-cgi php5-fpm php-pear php5-mcrypt
=====================

НЕ забыть изменить в /etc/php5/fpm/pool.d/www.conf параметр listen на

listen	= 127.0.0.1:9000

https://github.com/AeonRush/nginx-php5-fpm-config/blob/master/nginx/common/site#L21
