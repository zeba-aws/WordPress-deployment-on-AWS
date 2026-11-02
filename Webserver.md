# Now install and configure apache,wordpress
sudo yum install -y httpd
sudo service httpd start
wget https://wordpress.org/latest.tar.gz
tar -xzvf latest.tar.gz
# create a wp-config file from sample config file 

cd wordpress

cp wp-config-sample.php wp-config.php

vi wp-config.php

sudo dnf install -y httpd php php-fpm php-mysqli php-curl php-gd php-mbstring php-xml php-intl php-zip php-json wget

ls

sudo cp -r wordpress/* /var/www/html/

 cd /var/www/html/

 <img width="1191" height="615" alt="Keygenerte" src="https://github.com/user-attachments/assets/a25111ac-56c3-4690-9bd5-58b471b53e5d" />
 

sudo service httpd start


 <img width="1347" height="719" alt="wordpress" src="https://github.com/user-attachments/assets/2c70583d-14aa-4507-8207-2b3a4a8fea7e" />

<img width="1361" height="723" alt="sample" src="https://github.com/user-attachments/assets/912d4d3d-4c65-48b7-93f2-09397d51d24a" />
