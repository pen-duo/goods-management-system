## 商品后台管理系统
[效果演示地址:](http://47.119.156.87:3000/#/auth)

## 技术栈
前端技术栈:vue3 + vuex + vue-router + ES6/7 + scss + ant-design-vue 
网络请求:axios
服务端技术栈: koa2 
数据库: mongoose

## 参考文档
+ vue：Vue是一套用于构建用户界面的渐进式框架。
+ vuex：Vuex 是一个专为 Vue.js 应用程序开发的状态管理模式。
+ vue-router：Vue Router 是 Vue.js 官方的路由管理器。
+ scss：Scss 是一门 CSS 预处理语言，它扩展了 CSS 语言，增加了变量、Mixin、函数等特性，使 CSS 更易维护和扩展。
+ ant-design-vue：Antd,一套为开发者、设计师和产品经理准备的基于 Vue 的桌面端组件库。
+ axios：进行网络请求。
+ Koa  基于 Node.js 平台的下一代 web 开发框架 

## 前序准备
由于此项目是基于nodejs的前后端结合项目，你需要进行nodejs的相关准备工作。项目运行之前，请确保系统已经安装以下应用
(1) node(版本尽可能高)，请参考：[node的下载及安装](https://nodejs.org/zh-cn/)。

## 开发

git clone https://github.com/pen-duo/goods-management-system

cd goods-management-system/book-mgr-fe (1)npm install --> (2)npm run serve

cd goods-management-system/book-mgr-be (1)npm install --> (2)npm run dev

cd goods-management-system/book-mgr-be/init (1)node index.js

### 本地运行

npm run serve 运行之后，会默认打开本地访问路径：http://localhost:8080

### 发布

npm run bulid (生成打包之后的项目文件,此文件主要用于项目部署)。

## 演示

测试账号:
1.管理员: admin / password: admin

2.成员: editor / password: 123456

注意：

admin：拥有最高权限，可以查看所有的页面和按钮；

editor：只有被赋予权限的页面和按钮才可以看到
