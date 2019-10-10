# interest-pro
interest项目的微服务版
```
当master分支代码为含有kafka版本，需要无kafka版本代码，下载tag 1.0.0 版本代码。
```
euraka：http://localhost:8761/
用户：http://localhost:8083/interest/user/swagger-ui.html#/
博客：http://localhost:8086/interest/blog/swagger-ui.html#/
鉴权：http://localhost:8082/interest/auth/swagger-ui.html#/

发布访问：
App running at:
  - Local:   http://localhost:8090/
  - Network: http://192.168.0.230:8090/
  后端管理：
  http://localhost:8091/
  
  admin、admin  user/user

前端界面开发
注：需要安装nodejs

启动：(注意：最好换cnpm，npm我这边启动报404)
命令行进入项目文件夹
运行npm install（初次启动）
运行npm run serve启动前端工程
打包命令： 运行npm run build
=====================
如果你项目启动有错误：
项目启动报错，请试一下用管理员权限输入命令。
启动报错：Invalid options in vue.config.js: "publicPath" is not allowed，请把vue.config.js中的publicPath改成baseUrl。
install报错，请换成cnpm

## 项目介绍
  该项目为前后端分离项目，前端vue，后端Spring Cloud。
  
## 已有功能介绍
  1. bbs网站
  2. blog网站
  3. 后台管理系统
  
## 项目展示
  项目展示地址为我的网站：https://www.lovemtt.com/ （服务器配置低，首次加载会有点慢，登录请用github/QQ第三方登录。）
  
## 项目目录结构
- bbs网站+blog网站前端源码是该目录下的interest-web，前端详细介绍地址：https://github.com/smallsnail-wh/interest-pro/tree/master/interest-web
- 后台管理系统前端源码是该目录下的interest-manage，前端详细介绍地址：https://github.com/smallsnail-wh/interest-pro/tree/master/interest-manage
- 后端源码是该目录下的interest-cloud，后端详细介绍地址：https://github.com/smallsnail-wh/interest-pro/tree/master/interest-cloud

## 项目架构图
![interest-pro架构图](https://github.com/smallsnail-wh/images/blob/master/Untitled%20Diagram.png)
