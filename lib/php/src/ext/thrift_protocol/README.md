## Readme

在此目录下执行 phpize 

即可生成编译环境

```
shell> /path/to/phpize
shell>./configure --with-php-config=php-config
shell> make
shell> sudo make install
....
Installing shared extensions:     /usr/lib/php/extensions/no-debug-non-zts-20121212/
shell> ls /usr/lib/php/extensions/no-debug-non-zts-20121212/ | grep thrift_protocol
thrift_protocol.so
说明已生成扩展库
shell> sudo vim /path/to/php.ini
添加一行扩展
extension=thrift_protocol.so

``` 
