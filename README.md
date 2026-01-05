# script.sh


yum install httpd -y
systemctl  start httpd
systemctl enable httpd
echo "hello from Git and jenkins" >> /mnt/index.html
chmod 777 /mnt/index.html
 cp  /mnt/index.html /var/www/html
