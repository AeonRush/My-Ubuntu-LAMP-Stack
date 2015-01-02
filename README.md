Настройка связки NGINX + PHP-FPM (Dev)
=====================
НЕ забыть изменить в /etc/php5/fpm/pool.d/www.conf параметр listen на

listen	= 127.0.0.1:9000
