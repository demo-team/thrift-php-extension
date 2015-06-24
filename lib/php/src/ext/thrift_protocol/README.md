## Readme

在此目录下执行 phpize 

即可生成编译环境

```
shell> /path/to/phpize
shell> make
shell> sudo make install
....
shell> sudo vim /path/to/php.ini
添加一行扩展
extension=thrift_protocol.so

``` 
