
##
提供了各种消息队列服务，包含：NSQ

### 目录结构
```
+-- mq                    // 队列目录
|
+-- pub                   // 消息队列生产方工厂，可以生产各种队列的生产方
|
+-- sub                   // 消息队列消费方工厂，可以生产各种队列的消费方
|
+-- nsq                   // nsq消息队列，可由队列工厂生产出实例
|   +-- ...               // 参考nsq项目README
|
+-- mq.go                 // 消息队列对外接口
|
+-- nsq                   // nsq消息队列实例
|   +-- common            // topic，channel，公共接口
|   +-- consumer          // 消费方
|   +-- publisher         // 生产方
|
```

### 对外接口服务实例
``` golang

```
