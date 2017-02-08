phpv
====

This simple BASH script will simplify switching between 5.* and 7.* php branches on Ubuntu.
Corresponding PHP versions should be already installed.

INSTALLATION
------------
Put `phpv` file into your `/usr/bin/` directory and make it executable.
You can do this with following command (under root):

```
wget -O /tmp/phpv.zip https://github.com/czt08883/switch-php-version/archive/master.zip; unzip /tmp/phpv.zip -d /tmp/phpv; cp /tmp/phpv/switch-php-version-master/phpv /usr/bin; chmod a+x /usr/bin/phpv`
```

USAGE
-----
     (sudo) phpv [OPTION]

Possible options:

    -v, v, --version        show current PHP version
    -5, 5                   switch PHP version to 5.*
    -7, 7                   switch PHP version to 7.*
    

PHP VERSIONS
------------
In case you haven't installed both PHP versions yet, and you don't know how to do it
[this](https://lornajane.net/posts/2016/php-7-0-and-5-6-on-ubuntu) little guide might help.

