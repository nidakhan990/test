## conf file for domain..com.conf

<br> <tab><tab><pre><code><VirtualHost *:80>
    ServerAdmin admin@example.com
    ServerName domain.com
    ServerAlias www.domain.com
    DocumentRoot /var/www/domain.com/public_html
    ErrorLog /var/log/httpd/domain.com_error.log
    CustomLog /var/log/httpd/domain.com_access.log combined
</VirtualHost>
</pre></code><br>

![Screenshot from 2024-04-23 02-32-45](https://github.com/nidakhan990/test/assets/164150254/9f6e9bff-2f61-4565-9832-eb208ae6068b)


## create one file from these two in conf.d <br>
![Screenshot from 2024-04-23 02-32-55](https://github.com/nidakhan990/test/assets/164150254/331b27f7-cf0b-4ab8-8fe4-4532f71aa5ee)


<br> <tab><tab><pre><code>#!/bin/bash
set -x
path="/etc/httpd/conf.d/domain.com.conf"
path2="/etc/httpd/conf.d/domain2.com.conf"

if [ -f "${path}" ]; then
   sudo rm -f "${path}"  # Remove the existing file
   sudo cp /root/domain2.com.conf "${path2}"  # Copy the new configuration file
   sudo systemctl restart httpd

elif [ -f "${path2}" ]; then
   sudo rm -f "${path2}"  # Remove the existing file
   sudo cp /root/domain.com.conf "${path}"  # Copy the new configuration file
   sudo systemctl restart httpd
fi
</pre></code><br>

---------------------------------------------
## Cron tab
Run as a root
<br> <tab><tab><pre><code>* * * * * /bin/bash /root/web.sh > output.log  2>&1
</pre></code><br>
