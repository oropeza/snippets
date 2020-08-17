
## Respaldo

tar cvzf tarball.tar.gz directory/  
mysqldump -u root -p  mydatabasename > moodle-database.sql


https://www.linode.com/docs/platform/disk-images/copying-a-disk-image-over-ssh/

 
## Dir

rm -rf mydir

## Fail2ban
```
fail2ban-client status
fail2ban-client set YOURJAILNAMEHERE unbanip IPADDRESSHERE
```
eJEMPLO
fail2ban-client set sshd unbanip IPADDRESSHERE

## SSL
Generar llave para SSL    
```
mkdir /etc/ssl/localcerts  
openssl req -new -newkey rsa:4096 -days 365 -nodes -keyout example.com.key -out example.com.csr
```

## db
Crear usuario y darle permisos
CREATE USER 'nombre_usuario'@'localhost' IDENTIFIED BY 'tu_contrasena';
GRANT ALL PRIVILEGES ON * . * TO 'nombre_usuario'@'localhost';



rake db:create db:migrate db:seed RAILS_ENV=production


RAILS_ENV=production bundle exec rake assets:precompile



bundle exec puma -p 80 -d  
pgrep -f '^([^ ]*/)?puma '^C  
bundle exec pumactl -p 22353 stop  
