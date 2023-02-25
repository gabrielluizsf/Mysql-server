# Mysql Server

## How to Install && Setup

```bash
sudo apt-get install mysql-server
```

```mysql
sudo mysql -h localhost -u root -p
```

```mysql
mysql> SET PASSWORD FOR ‘root’@'localhost’ = PASSWORD(‘atuapassword’):
```

```bash
  sudo apt-get install libapache2-mod-auth-mysql php5-mysql phpmyadmin
```

```bash
gksudo gedit /etc/php5/apache2/php.ini
```

```php
//Procure pela linha onde tem a seguinte frase…

;extension=mysql.so

//e substitua por esta:

extension=mysql.so
```


```bash
sudo /etc/init.d/apache2 restart
```
