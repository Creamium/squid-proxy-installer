# squid-proxy-installer

Auto install Squid 3 proxy on

+ Ubuntu 14.04
+ Ubuntu 16.04
+ Ubuntu 18.04
+ Ubuntu 18.10
+ Ubuntu 19.04
+ Debian 8 

## Install Squid

To install, run the script

```
wget https://raw.githubusercontent.com/Juxstin/squid-proxy-installer/master/squid3-install.sh
chmod 755 squid3-install.sh
sudo ./squid3-install.sh
```

# Create Users

To create users, run

```
/usr/bin/htpasswd -b -c /etc/squid/passwd USERNAME_HERE PASSWORD_HERE
```

To update password for am existing user, run

```
/usr/bin/htpasswd /etc/squid/passwd USERNAME_HERE
```


replace USERNAME_HERE and PASSWORD_HERE with your desired user name and password.
