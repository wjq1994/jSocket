# jSocket
javascript use socket

如何使用：

1.创建socket服务器

2.浏览器直接打开 JSocket/samples/client/example/example.html 查看效果

原理：

js不能直接使用socket协议（websocket不是socket）

flash可以使用socket协议，利用as文件

js和flash之间可以相互调用（actionscript语法 ExternalInterface.addCallback ExternalInterface.call）

js调用flash，间接完成js使用socket
