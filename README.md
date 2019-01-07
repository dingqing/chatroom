# chatroom
基于Swoole实现简易聊天室

参考：[Swoole文档](https://wiki.swoole.com/)

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
- 打开多个浏览器/标签页，分别访问 [localhost:8000](localhost:8000)，假装多人在聊天