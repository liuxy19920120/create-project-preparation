## node安装
**[参考菜鸟教程](http://www.runoob.com/nodejs/nodejs-install-setup.html)**
>1. node.js安装包下载 https://nodejs.org/en/download/
>2. 安装node到计算机 可以自定义安装路径
>3. cmd下查看计算机环境变量输入path，确定node安装路径
>4. 查看node版本号 node --version
>5. node创建应用
` var http = require('http');
  http.createServer(function (request, response) {
    // 发送 HTTP 头部 
    // HTTP 状态值: 200 : OK
    // 内容类型: text/plain
    response.writeHead(200, {'Content-Type': 'text/plain'});
    // 发送响应数据 "Hello World"
    response.end('Hello World\n');
 }).listen(8888);
 // 终端打印如下信息
 console.log('Server running at http://127.0.0.1:8888/');
`
>6. 执行 node server.js 查看服务是否正常启动


