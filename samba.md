



Instalar Samba

sudo apt-get install samba

;sudo adduser --no-create-home --disabled-password --disabled-login sambausername

samba-tool user add USERNAME-HERE
sudo smbpasswd -a sambausername


sudo service smbd force-reload


sudo chown -R nobody:nogroup /samba/public
sudo chmod -R 0775 /samba/public
sudo service smbd restart
