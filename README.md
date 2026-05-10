![](qrcode.png)

# [social-media-platform](https://github.com/LafeLabs/social-media-platform/)

## Linux Install:

 - [https://etcher.balena.io/#download-etcher](https://etcher.balena.io/#download-etcher)
 - [https://ubuntu.com/download/desktop](https://ubuntu.com/download/desktop)


```
sudo apt update
sudo apt install apache2 -y
sudo apt install php libapache2-mod-php -y
cd /var/www/html
sudo rm index.html
sudo apt-get install curl
sudo curl -o replicator.php https://raw.githubusercontent.com/lafelabs/social-media-platform/refs/heads/main/replicator.php
cd ..
sudo chmod -R 0777 *
cd html
php replicator.php
sudo chmod -R 0777 *
ln -s /var/www/html ~/Desktop/html
```

## XAMPP

 - [https://www.apachefriends.org/](https://www.apachefriends.org/)