#React-aixianfeng

##概述
本项目有两个环境，一个是前端开发环境(端口是8080)，一个是server服务环境(端口是3000)。
该项目是使用`react`全家桶模仿的一个电商App，功能主要有注册登录，搜索，商品分类，排序，购物车，修改信息等。

###技术栈 :
-  基础列表库： `react`
-  路由 ： `react-router`
-  数据管理：`react-redux` + `redux-thunk`+`redux-logger`中间件
-  路由信息同步 ： `react-router-redux`
-  样式 ： `less`
-  后台： `node.js` + `express`


##运行方式
***
使用npm安装依赖： `npm install`

***
###开发环境运行方式
***
客户端： 主目录下运行 `npm run dev`
服务器端 ： server目录下运行`node server.js`
***

##项目预览

![Image text](http://chuantu.biz/t6/158/1511680542x-1404817507.gif)


***
##文件目录结构

├─build 	 					项目打包文件
├─server	  					后台
│  └─mock  				模拟数据
│  └─server.js  			node.js服务应用
├─src							前台文件
│  ├─api						前台接口
│  ├─components  		公共组件
│  ├─container	   		项目内容组件
│  ├─images 				图片
│  └─store					状态仓库
│      ├─actions			动作库
│      └─reducers			状态库
│      └─action-types  动作类型
│      └─index				状态仓库根组件
│  └─utils					工具箱
├─static						静态资源文件
├─index.html				项目根页面
└─webpack.config.js	webpack配置文件




