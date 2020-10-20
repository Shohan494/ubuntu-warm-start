PHP 7.4
========

```
sudo apt install php php-cli php-fpm php-json php-pdo php-mysql php-zip php-gd  php-mbstring php-curl php-xml php-pear php-bcmath

sudo apt-get install mysql-server

sudo apt-get install mysql-server
sudo mysql_secure_installation

sudo mysql -u root -p

CREATE USER 'admin'@'localhost' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON *.* TO 'admin'@'localhost' WITH GRANT OPTION;
FLUSH PRIVILEGES;

mysql -u admin -p

sudo apt install curl php-cli php-mbstring git unzip

cd ~

curl -sS https://getcomposer.org/installer -o composer-setup.php

HASH=c31c1e292ad7be5f49291169c0ac8f683499edddcfd4e42232982d0fd193004208a58ff6f353fde0012d35fdd72bc394

php -r "if (hash_file('SHA384', 'composer-setup.php') === '$HASH') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"

sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer

sudo chown -R $USER ~/.composer/

composer global require laravel/installer

echo 'export PATH="$PATH:$HOME/.composer/vendor/bin"' >> ~/.bashrc

laravel new hello-world

sudo snap install sublime-text --classic

sudo apt install phpmyadmin php-mbstring php-zip php-gd php-json php-curl

```

#### if error occurs

```
sudo apt install phpmyadmin

sudo mysql

mysql -u root -p

mysql > UNINSTALL COMPONENT "file://component_validate_password";
```
