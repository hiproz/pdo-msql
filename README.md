# pdo-msql
a branch of PDO_MYSQL-1.0.2,make little change for the building

[PDO_MYSQL-1.0.2 original code download](http://pecl.php.net/get/PDO_MYSQL-1.0.2.tgz)

for the original source code you shoul buld as:
```
phpize
./configure --with-php-config=/usr/bin/php-config --with-pdo-mysql=/usr/
make && make install
```

for the not foud problem of mysql, you should install the mysql develop libs:
>yum install mysql-devel

for the mysql headers ,you should copy the include file of mysql to the root of this code or create a link:
>ln -s xxx xxx

for the other file path problems, i change the code manually, so this is a changed buile content directory that has build successfull.

have fun!
