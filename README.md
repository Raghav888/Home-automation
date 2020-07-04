# Home-automation
sudo apt-get update && sudo apt-get upgrade

sudo apt-get install python-dev
sudo apt-get install python-rpi.gpio

sudo apt-get install apache2 php5 libapache2-mod-php5

sudo service apache2 restart

sudo nano /etc/sudoers
 add to bottom of file:  www-data ALL=(root) NOPASSWD:ALL

put index file in wwww folder by replaceing existing index file.
