# linux

## komande
nginx cache :
https://www.digitalreborn.com/fix-nginx-helper-fastcgi-disk-cache-not-purge/
https://snippets.webaware.com.au/snippets/purging-nginx-cache-users-differ/
https://www.linode.com/docs/guides/how-to-use-nginx-fastcgi-page-cache-with-wordpress/

/etc/init.d/webmin start

sudo systemctl restart nginx
fuser -k 80/tcp
fuser -k 443/tcp

tail -f /var/log/messages

win:
mdsched.exe - test memorije


sudo service php7.--fpm restart

sudo ufw allow 9444/tcp
kill -9 pid

screen -S imeSesije
CTRL+a CTRL+d

screen -r

sudo nano /etc/systemd/system/mwc.service
systemctl daemon-reload
sudo systemctl start mwc

ps aux | grep mwc

sudo systemctl enable mwc.service

komanda za pretragu :
grep -rl 'screen-reader-text'

tail -f /var/log/mail.log
