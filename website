
#############################[ SCRIPT ]####################################################
#!/bin/bash
set -x
path="/etc/apache2/sites-enabled/domain2.com.conf"
path2="/etc/apache2/sites-enabled/domain.com.conf"

if [ -f "${path}" ]; then
   sudo a2dissite domain2.com.conf
   sudo a2ensite domain.com.conf
   sudo systemctl restart apache2
elif [ -f "${path2}" ]; then
   sudo a2dissite domain.com.conf
   sudo a2ensite domain2.com.conf
   sudo systemctl restart apache2
fi
#############################[ SCRIPT ]####################################################

#############################[ CRONTAB ]####################################################


* * * * * /bin/bash /root/web.sh > output.log  2>&1

#############################[ CRONTAB ]####################################################
