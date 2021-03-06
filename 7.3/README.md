[![Docker Pulls](https://img.shields.io/docker/pulls/zaherg/php-swoole.svg)](https://hub.docker.com/r/zaherg/php-swoole/) [![](https://images.microbadger.com/badges/image/zaherg/php-swoole:7.3.svg)](https://microbadger.com/images/zaherg/php-swoole:7.3 "Get your own image badge on microbadger.com") [![](https://images.microbadger.com/badges/version/zaherg/php-swoole:7.3.svg)](https://microbadger.com/images/zaherg/php-swoole:7.3 "Get your own version badge on microbadger.com") [![](https://images.microbadger.com/badges/commit/zaherg/php-swoole:7.3.svg)](https://microbadger.com/images/zaherg/php-swoole:7.3 "Get your own commit badge on microbadger.com")  [![](https://img.shields.io/github/last-commit/linuxjuggler/php-docker-swoole.svg)](https://github.com/linuxjuggler/php-docker-swoole)

# PHP Docker Swoole

This should contain all the images that I'll try to build and push to docker.

## Images description

Those images contain PHP 7.x based on alpine with MySQL, PostgreSQL, Redis, GD, [Swoole](https://www.swoole.co.uk/#get-started) enabled and Composer already installed

## Runing the image:

Then run the docker and specify the env file that you have created like this

```
docker run --env-file .env zaherg/php-swoole:<version>
```

## .env.example

```
PHP_XDEBUG_DEFAULT_ENABLE=0
PHP_XDEBUG_REMOTE_ENABLE=0
PHP_XDEBUG_REMOTE_HOST=127.0.0.1
PHP_XDEBUG_REMOTE_PORT=9001
PHP_XDEBUG_REMOTE_AUTO_START=0
PHP_XDEBUG_REMOTE_CONNECT_BACK=0
PHP_XDEBUG_IDEKEY=docker
PHP_XDEBUG_PROFILER_ENABLE=0
PHP_XDEBUG_PROFILER_OUTPUT_DIR=/tmp
```

## Installed modules information

It has the following modules:

[PHP Modules]

1. Core 
1. ctype  
1. curl 
1. date 
1. dom  
1. fileinfo 
1. filter 
1. ftp  
1. gd 
1. hash 
1. iconv  
1. intl 
1. json 
1. libxml 
1. mbstring 
1. mysqlnd  
1. openssl   
1. pcre 
1. PDO  
1. pdo_mysql  
1. pdo_pgsql  
1. pdo_sqlite 
1. pgsql 
1. Phar 
1. posix  
1. readline 
1. redis  
1. Reflection 
1. session  
1. SimpleXML  
1. sodium
1. SPL  
1. sqlite3  
1. standard 
1. swoole
1. tokenizer  
1. xml  
1. xmlreader  
1. xmlwriter  
1. zip  
1. zlib
