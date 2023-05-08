# RocketMQ 相关实践 
参考url：https://weread.qq.com/web/reader/0d732fd0813ab78ecg0198a7kf03328d0250f033ab37c722
书名：SpringCloud微服务快速上手
1.  下载windows 下课运行在本地 bin 下的命令 (运行 server, broker)
2.  搭建rocketmq的后台UI管理系统
$ git clone https://github.com/apache/rocketmq-externals.git
Cloning into 'rocketmq-externals'…
remote: Enumerating objects: 33, done.
remote: Counting objects: 100% (33/33), done.
remote: Compressing objects: 100% (20/20), done.
remote: Total 19009 (delta 4), reused 14 (delta 2), pack-reused 18976
Receiving objects: 100% (19009/19009), 33.27 MiB | 51.00 KiB/s, done.
Resolving deltas: 100% (7416/7416), done.
Updating files: 100% (6192/6192), done.
3.  简单的消息发送（生产） 和消息接收（消费）
