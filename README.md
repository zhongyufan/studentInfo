# 信息管理
## 技术栈
- 前端
  - Bootstrap 4.4.1
  - jQuery 3.5.1
- 后端
  - node.js 12.16.3
- 数据库
  - MongoDB 4.3.6
- 打包
  - gulp 4.0.2

## 实现功能
自适应PC端、移动端  
支持对学生信息的添加、修改、删除操作

## 运行
数据库默认使用test集合  
首次运行需要在根目录安装包 `npm install`  
在config.js中修改数据库连接集合

## 文件目录
```
.
├── README.md
├── app.js
├── config.js
├── gulpfile.js
├── model
│   ├── connect.js
│   └── user.js
├── package-lock.json
├── package.json
├── public
│   ├── css
│   │   ├── bootstrap.css
│   │   ├── list.css
│   │   └── main.css
│   └── js
│       ├── bootstrap.js
│       └── jquery.js
├── route
│   └── route.js
└── view
    ├── add.art
    ├── list.art
    └── updata.art
```