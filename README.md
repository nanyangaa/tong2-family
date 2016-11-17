# tong2-family

> 使用vue、vuex、vue-router、echarts搭建的一个数据展示平台   
> 不支持IE8及其以下版本，单页面应用      
> 对华科电信大二学生的做了一些调查，对调查结果进行可视化展示，同时分析了通信1502班的群聊记录，得到班级群聊活跃度等信息。

## 运行步骤

``` bash
# 安装依赖
npm install

# 在本地启动服务，并且通过localhost:8080地址进行访问
npm run dev

# 编译并压缩代码便于发布
npm run build

# 运行单元测试
npm run unit
``` 

## 演示
![演示](https://github.com/hieeyh/tong2-family/blob/master/show.gif)
## 在线访问
[]()   
**注意**：只有用通信1502班同学的qq号登陆才能看到我的群聊活跃时间

## 源码说明
```
.
|-- IM_analyze                       // 用python进行群聊数据分析的相关代码
|-- build                            // 项目构建相关代码
|-- config                           // 项目开发环境配置
|-- src                              // 源码目录                     
|   |-- components                   // vue公共组件
|   |-- store                        // vuex的状态管理
|       |-- store.js                 // 加载各种store模块
|       |-- login.js                 // 登录状态相关store
|       |-- user.js                  // 用户相关store
|   |-- App.vue                      // 页面入口文件
|   |-- main.js                      // 程序入口文件，加载各种公共组件
|-- static
|   |-- data                         // 群聊分析得到的数据用于数据可视化
|-- .babelrc                         // ES6语法编译配置
|-- .editorconfig                    // 定义代码格式
|-- .gitignore                       // git上传需要忽略的文件格式
|-- README.md                        // 项目说明
|-- favicon.ico 
|-- index.html                       // 入口页面
|-- package.json                     // 项目配置相关信息
.
```

## 教程
我的博客：[]()
