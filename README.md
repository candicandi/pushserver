# pushserver

pushserver监听websocket连接，同时通过Mqtt向Apollo订阅消息，一旦有消息进来就转发给websocket客户端
在Apollo和client之间怎加pushserver的好处是，pushserver可以做很多逻辑处理，同时也能减少Apollo的暴露和压力。

