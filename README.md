# z-im

springboot、netty、protobuf、redis、rocketmq实现的分布式即时消息系统

server1、server2代码一致，模拟启动两个分布式服务，启动时需配置redis和rocketmq

client1、client2代码一致，模拟启动两个连到不通服务器的客户端

通过client1和client2的controller可用浏览器模拟socket消息发送