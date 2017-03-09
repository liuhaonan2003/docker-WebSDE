FROM php:latest
# 安装扩展
RUN pecl install swoole \
    & redis 
# 启用扩展
RUN docker-php-ext-enable swoole \
    & redis

