# chatroom
基于Swoole实现简易聊天室

## 参考
<a href="https://wiki.swoole.com/" target="_blank">Swoole文档</a>

## 安装
### 环境要求
- PHP >= 7.0
- Swoole
- composer
### 开始
- composer install
- 启动 websocket
```
    php webim_server.php
```
- 启动 PHP 内置服务器
```
    cd ./public
    php -S localhost:8000
```