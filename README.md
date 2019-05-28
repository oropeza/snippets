

Generar llave para SSL  
openssl req -new -newkey rsa:4096 -days 365 -nodes -keyout example.com.key -out example.com.csr


Crear usuario y darle permisos
CREATE USER 'nombre_usuario'@'localhost' IDENTIFIED BY 'tu_contrasena';
GRANT ALL PRIVILEGES ON * . * TO 'nombre_usuario'@'localhost';



rake db:create db:migrate db:seed RAILS_ENV=production


RAILS_ENV=production bundle exec rake assets:precompile



bundle exec puma -p 80 -d
pgrep -f '^([^ ]*/)?puma '^C
bundle exec pumactl -p 22353 stop
