## npm安装
**[参考菜鸟教程](http://www.runoob.com/nodejs/nodejs-npm.html)**
>1. 新版的node已经集成了npm
>2. 查看版本号
    npm -v
>3. 升级npm 
npm install npm -g
>4. 淘宝镜像 
cnpm install npm -g
>5. npm安装模块 
npm install(i) 模块名
>6. 安装node.js web框架 
npm i express
>7. 全局安装和本地安装
**npm install express          # 本地安装
npm install express -g   # 全局安装**
8. 查看所有全局安装的模块
 npm list -g
9. 查看模块的版本号
 npm list 模块名
10.更新模块
 npm update express
11.npm 生成package.json文件
npm init

**使用淘宝 NPM 镜像
大家都知道国内直接使用 npm的官方镜像是非常慢的，这里推荐使用淘宝 NPM 镜像。
淘宝 NPM 镜像是一个完整 npmjs.org 镜像，你可以用此代替官方版本(只读)，同步频率目前为 10分钟 一次以保证尽量与官方服务同步。
你可以使用淘宝定制的 cnpm (gzip 压缩支持) 命令行工具代替默认的 npm:
 npm install -g cnpm --registry=https://registry.npm.taobao.org
cnpm install [name]**


