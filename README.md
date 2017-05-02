


=========================================================================================
###nginx
##Getting Started
https://www.nginx.com/resources/wiki/start/
http://nginx.org/en/docs/

#nginx.conf
#proxy_conf
#fastcgi_conf
www.nginx.com/resources/wiki/start/topics/examples/full/




-----------------------------------------------------------------------------------------
#PID
cat /usr/local/nginx/logs/nginx.pid

#load nginx.conf
/usr/local/nginx/sbin/nginx -c /usr/local/nginx/conf/nginx.conf

#Kill All
pkill -9 nginx

#check config file
nginx -t -c /usr/local/nginx/conf/nginx.conf








