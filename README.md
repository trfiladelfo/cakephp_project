# CakePHP

- CakePHP 2.7.6
- CakePHP 3.1.2

###Configuração para o CakePHP 2.7.6
Configurar o timezone:
date.timezone = America/Sao_Paulo

###Configuração para o CakePHP 3.1.2 com Composer
Descomentar no php.ini:
 extension=php_mbstring.dll,
 extension=php_openssl.dll,
 extension=php_intl.dll,
 zend_extension=php_opcache.dll,

####Composer
Instalação, precisa estar com a variável de ambiente configurada do php

 php -r "readfile('https://getcomposer.org/installer');" | php
 
 php composer.phar create-project --prefer-dist cakephp/app [nome da aplicacao]

----------------------

Usei o MAMP como provedor web/php
