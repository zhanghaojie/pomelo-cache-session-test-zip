pomelo-cache-session-test-zip
=============================


下载项目
解压zip后直接进入game-server 启动服务器

在测试端里
```
pomelo.request("connector.entryHandler.entry", {bindMore: true}, function(result) {
      console.log(result);
})
```
先执行类似的命令进入connector。主要是为了模拟在session上push一些信息，模拟实际情况

下面是测试对象
```
pomelo.request("chat.chatHandler.chat", {msg: "hello chat"}, function(result) {})
```
重点循环测试这个，看服务器对比现在官网上有多大提升
