## Server Config
```
sudo apt-get -y update && sudo apt-get -y upgrade
sudo timedatectl set-timezone  America/Mexico_City
```
## Hostname
```
sudo hostnamectl set-hostname $NAME$
nano /etc/hosts
```

## user
```
sudo adduser deploy
sudo adduser deploy sudo
su deploy
```

#RUBY RAILS MYSQL
https://gorails.com/setup/ubuntu/18.04

sudo chown -R deploy:deploy vulnerabilidad
chmod 0777 module_installation/

>>  ~/.bashrc
inicio
cd /srv
fin

INSTALL NGIX 

sudo apt install nginx

PASSANGER
https://www.phusionpassenger.com/library/install/nginx/install/oss/bionic/


Ref
https://www.vultr.com/docs/how-to-install-and-configure-ruby-with-rbenv-rails-mariadb-nginx-ssl-and-passenger-on-ubuntu-17-04
https://www.phusionpassenger.com/library/install/nginx/install/oss/bionic/
https://askubuntu.com/questions/320444/setting-up-rbenv-properly


https://mediatemple.net/community/products/developer/204405534/install-nginx-on-ubuntu
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-rails-app-with-passenger-and-nginx-on-ubuntu-14-04
https://www.hugeserver.com/kb/how-serve-ruby-rails-app-nginx-passenger-ubuntu16/
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-rails-app-with-passenger-and-nginx-on-ubuntu-14-04
