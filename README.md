sudo yum install httpd
sudo wget https://dev.mysql.com/get/mysql57-community-release-el7-11.noarch.rpm
sudo yum localinstall mysql57-community-release-el7-11.noarch.rpm 
sudo yum install mysql-community-server
systemctl start mysqld.service
