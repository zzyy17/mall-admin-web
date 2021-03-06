# mall-admin-web

## 说明

> 基于vue+element的电商后台管理系统，完整实现了整个流程。

> 该项目为前后端分离项目，搭建步骤具体参考后端项目[传送门](https://github.com/macrozheng/mall)。

> 如果该项目对您有帮助，您可以点右上角 "Star" 支持一下 谢谢！

> 或者您可以 "follow" 一下，该项目将持续更新，不断完善功能。

> 如有问题或者好的建议可以在 Issues 中提。

## 前言

`mall`项目后台管理系统的前端项目
[传送门](https://github.com/macrozheng/mall)。

## 项目介绍

`mall-admin-web`是一个电商后台管理系统的前端项目，基于Vue+Element实现。
主要包括商品管理、订单管理、会员管理、促销管理、运营管理、内容管理、统计报表、财务管理、权限管理、设置等功能。

## 项目演示

项目在线演示地址：[www.macro.com/mall-admin/index.html](http://39.98.69.210/index.html)  

![https://github.com/macrozheng/mall/blob/master/document/resource/mall-admin.gif](https://github.com/macrozheng/mall/blob/master/document/resource/mall-admin.gif)

## 技术选型

技术 | 说明 | 官网
----|----|----
Vue | 前端框架 | [https://vuejs.org/](https://vuejs.org/)
Vue-router | 路由框架 | [https://router.vuejs.org/](https://router.vuejs.org/)
Vuex | 全局状态管理框架 | [https://vuex.vuejs.org/](https://vuex.vuejs.org/)
Element | 前端UI框架 | [https://element.eleme.io/](https://element.eleme.io/)
Axios | 前端HTTP框架 | [https://github.com/axios/axios](https://github.com/axios/axios)
v-charts | 基于Echarts的图表框架 | [https://v-charts.js.org/](https://v-charts.js.org/)
Js-cookie | cookie管理工具 | [https://github.com/js-cookie/js-cookie](https://github.com/js-cookie/js-cookie)
nprogress | 进度条控件 | [https://github.com/rstacruz/nprogress](https://github.com/rstacruz/nprogress)

### 项目布局

``` lua
src -- 源码目录
├── api -- axios网络请求定义
├── assets -- 静态图片资源文件
├── components -- 通用组件封装
├── icons -- svg矢量图片文件
├── router -- vue-router路由配置
├── store -- vuex的状态管理
├── styles -- 全局css样式
├── utils -- 工具类
└── views -- 前端页面
    ├── home -- 首页
    ├── layout -- 通用页面加载框架
    ├── login -- 登录页
    ├── oms -- 订单模块页面
    ├── pms -- 商品模块页面
    └── sms -- 营销模块页面
```

## 搭建步骤

- 该项目为前后端分离项目，要先搭建后台项目才可正常访问接口，搭建后台参考后端项目[传送门](https://github.com/macrozheng/mall);
- 克隆源代码到本地，使用IDEA打开，并完成编译;
- 运行命令：npm run dev,访问地址：[http://localhost:8090](http://localhost:8090) 即可打开后台管理系统页面；
- 考虑到后台搭建的复杂性，本项目已开放后台在线API，只需要将config/dev.env.js文件中的BASE_API改为[http://39.98.69.210](http://localhost:39.98.69.210)即可免后台搭建。

## 许可证

[MIT](https://github.com/macrozheng/mall-admin-web/blob/master/LICENSE)

Copyright (c) 2018-2019 macrozheng
