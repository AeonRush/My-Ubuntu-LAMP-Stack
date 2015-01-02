Настройка связки NGINX + PHP-FPM (Dev)
=====================
НЕ забыть изменить в /etc/php5/fpm/pool.d/www.conf параметр listen на

listen	= 127.0.0.1:9000

https://github.com/AeonRush/nginx-php5-fpm-config/blob/master/nginx/common/site#L21
