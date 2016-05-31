for php7:
vagrant@homestead:~$ git clone -b php7 https://github.com/phpredis/phpredis.git
vagrant@homestead:~$ sudo mv phpredis/ /etc/
vagrant@homestead:~$ cd /etc/phpredis
vagrant@homestead:/etc/phpredis$  phpize
vagrant@homestead:/etc/phpredis$ ./configure
vagrant@homestead:/etc/phpredis$ make && sudo make install
