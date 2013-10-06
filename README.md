onethink
========

cms framework

wwwroot
├─index.php     OneThink入口文件
├─Addons 插件目录
│  
├─Application 应用模块目录
│  ├─Admin 后台模块
│  │  ├─Conf 后台配置文件目录
│  │  ├─Common 后台函数公共目录
│  │  ├─Controller 后台控制器目录
│  │  ├─Model 后台模型目录
│  │  ├─Logic 后台模型逻辑目录
│  │  └─View 后台视图文件目录
│  │  
│  ├─Common 公共模块目录（不能直接访问）
│  │  ├─Conf 公共配置文件目录
│  │  ├─Common 公共函数文件目录
│  │  ├─Controller 模块访问控制器目录
│  │  └─Model 公共模型目录
│  │  
│  ├─Home Home 前台模块
│  │  ├─Conf 前台配置文件目录
│  │  ├─Common 前台函数公共目录
│  │  ├─Controller 前台控制器目录
│  │  ├─Model 前台模型目录
│  │  └─View 模块视图文件目录
│  │
│  └─User 用户模块（不能直接访问）
│     ├─Api 用户接口文件目录
│     ├─Conf 用户配置目录
│     ├─Common 后台函数公共目录
│     ├─Model 用户模型目录
│     └─Service 用户Service文件目录
│
├─Public 应用资源文件目录
│  ├─Admin 后台资源文件目录
│  │  ├─css 样式文件目录
│  │  ├─images 图片文件目录
│  │  └─js 脚本文件目录
│  │
│  ├─Home 前台资源文件目录
│  │  ├─css 样式文件目录
│  │  ├─images 图片文件目录
│  │  └─js 脚本文件目录
│  │
│  └─static 公共资源文件目录
│  
├─Runtime 应用运行时目录
├─ThinkPHP 框架目录
└─Uploads 上传根目录
  ├─Download 文件上传目录
  ├─Picture 图片上传目录
  └─Editor 编辑器图片上传目录
