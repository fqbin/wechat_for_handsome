# 微信公众号服务端 for handsome主题

本项目需要配合handsome主题的时光机使用

环境需求
PHP >= 7.1
PHP cURL 扩展
PHP OpenSSL 扩展
PHP SimpleXML 扩展
PHP fileinfo 扩展
PHP PDO_MYSQL 扩展

食用方法
安装
拷贝项目到你的服务器
打开 网址/install.php 安装
在公众号后台服务器配置填写服务器地址为 项目所在网址/server.php 并启用服务器配置
公众号发送绑定，点击链接填写相关信息进行绑定
配置完成，尽情使用吧！使用方法同handsome官方时光机发送公众号
使用
1.发送 绑定 进行绑定或修改绑定信息
2.向时光机发送消息
支持文字、图片、地理位置、链接四种消息类型。
其他消息类型等后续开发，暂不支持（如果发送了，会提示不支持该类型的，如语音消息）。
如果发送的是图片会自动将图片存放到typecho 的 usr/uploads/time 目录下。
支持发送私密说说。只需要在发送内容前加入#即可。 举例发送：#这是私密的说说，仅发送者可见。
连续发送多条信息
发送【开始】，开始一轮连续发送
发送【结束】，结束当前轮的发送
3.发送文章
输入【发文章】，开始文章发送，支持多条消息，支持多条消息图文混合
输入【结束】，结束文章发送
4.其他操作
发送 博客收到你的博客地址的链接
发送 发博客收到发博文的字的链接
发送 解除绑定 或 解绑 可删除掉你的绑定信息
发送 帮助 查看帮助信息

## 微信公众号服务端 for handsome主题
## *本项目需要配合handsome主题的时光机使用*
