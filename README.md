# apt
## Importing GPG keys for Dotdeb and MariaDB
```shell
wget http://www.dotdeb.org/dotdeb.gpg
cat dotdeb.gpg | apt-key add -
rm -f dotdeb.gpg
apt-key adv --recv-keys --keyserver keyserver.ubuntu.com 0xcbcb082a1bb943db
```