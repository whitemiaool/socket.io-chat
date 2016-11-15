# socket.io-chat
基于socket.io模块,nodejs的简单教程

#声明
这个模块是基于https://github.com/plhwin/nodejs-socketio-chat 所编写添加改进
主要添加了用户列表目录、本地手机运行

#教程
主要分为客户端（client文件目录下）和服务端（sever目录下）运行在本地

1  进入到sever模块安装所需要的模块 npm或cnpm(淘宝镜像)  install express  http socket.io http 

2  node index.js

3  访问localhost:3000

4  如果需要在手机端访问，则需要连接同一个局域网，并且将 client/client.js 中115行 this.socket = io.connect('localhost:3000')  localhost改为你本机的IP地址即可
