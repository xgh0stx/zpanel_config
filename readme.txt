
Description:

Configuration files for zpanel. This repo stores critical configuration for tune up purpose. 



zpanel config files            /etc/zpanel/configs
zpanel apache config files     /etc/zpanel/configs/apache/httpd.conf
zpanel virtual host file       /etc/zpanel/configs/apache/httpd-vhost.conf
zpanel website files            /etc/zpanel/panel
zpanel FTP config file          /etc/zpanel/configs/proftpd/proftpd-mysql.conf
zpanel log files                /var/zpanel/log/
zpanel users websites           /var/zpanel/hostdata/[zpanel-login/public_html/[sub_domain_tld]
zpanel custom static pages      /etc/zpanel/panel/etc/static/
zpanel themes                   /etc/zpanel/panel/etc/styles/


Apache config file              /etc/apache2/httpd.conf
Apache log files                /var/log/apache2/error.log


php.ini                        /etc/php5/apache2/error.log


mysql config file               /etc/mysql/my.cnf
mysql log file                  /var/logmysql/error.log



Apache user:group              www-data:www-data
run zpanel daemon              sudo /usr/bin/php -q   /etc/zpanel/panel/bin/daemon.php







