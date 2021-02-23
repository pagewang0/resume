## 汪聪

Email: cGFnZXdhbmcwQGdtYWlsLmNvbQ==(base64)

## 工作经验

### 衍界资讯（远程）2020.5 - 2020.7
- 负责后端开发，项目结构划分（前后端分离，nginx网关控制，静态文件cdn）和项目部署（dev：前海云，production：阿里云）。
- 百万级别数据的查询优化(mysql)，从技术与业务层面避免查询过慢。
- 邮件通知与定时任务。
- 上传文件与Excel解析。
- 在公司简报功能中涉及逻辑分支过多（20种）的情况下，使用mock数据的思路来覆盖每个逻辑分支。
- 日志(文件级)留痕与故障排查。

### 隆康科技 2019.9 - 2020.3
- IM服务端开发，基于socket.io开发的群聊服务。
- 为公司内其他服务提供消息推送，客户端（Web、Android、IOS、Windows）各平台提供接入服务和协调连接策略问题
- 排查项目中存在的socket对象内存泄露问题
- 压力测试，由于对项目的性能与稳定性有一定要求，在功能完备后，对项目进行压力测试，编写压测脚本，模拟多用户情况下的cpu、内存情况（基于并发100，单个节点用户连接数与消息数承载在3000左右）。
- 日志(文件级)留痕与故障排查。

### 德科信息 2017.12 - 2018.11
- 主要负责理财网店后端开发，工作涉及：API服务、定时任务、批处理脚本、测试用例，网关逻辑。
- 期间解决过内存泄露问题，主要涉及node特定版本中的http parse泄露，以及Mongoose特定版本的问题。
- 日志(kibana/自研系统)留痕与故障排查。

### 光音网络 2015.5 - 2016.6
- 数据统计业务的前端开发，使用React+Flux来实现后台管理页面。
- 广告业务的前后端开发，前端涉及淘宝客页面的编写，后端主要是存储各类上报数据。
- 解决过客户端时间不准问题，基于服务端时间使用相对值来进行校对。

## 项目经验

### ESG舆情预警（衍界资讯）
- 使用koa框架，数据库使用mysql，ORM使用sequelize，定时任务采用node-schedule。
- 使用的cookie-session来做用户身份标识。
- eslint规范代码风格。
- pm2做守护进程。
- number-precision来做计算，避免数据小数位的精度问题。

### IM服务（隆康科技）
- 使用socket.io来处理socket通信。
- koa对外提供http请求服务（主要是跨服务通信以及管理端控制）。
- 数据存储使用redis，mysql数据只读。
- 多节点使用socket.io-redis。
- 测试工具：mocha、chai、proxyquire、sinon、nock。测试覆盖率：nyc。
- pm2做守护进程。
- 部署使用jenkins。

### 理财网店（德科信息）
- 项目采用微服务结构，主体是express(Promise)，部分迁出的新服务采用koa(async/await)。
- 数据库使用mongodb，读写分离，redis做缓存。
- 网关使用OpenResty，用于单点登陆、反向代理。
- 使用redis做消息队列来离线处理消息推送服务。
- 测试使用ava和nock。
- 编写Dockerfile和使用docker容器部署。
- 使用Gitlab来做CI/CD。

### 淘宝客（光音网络）
- 服务端使用express+mongodb.
- 前端使用bootstrap+jquery。
- 定时拉取商品信息。
- 编写dockerfile和使用docker部署.

## 工作以外

### 腾讯滑动验证码破解
- 使用python中的selenium和openCV图形处理，针对背景图和滑动图做二值化，然后反转滑动图的色值，最后做像素匹配，得到滑动图与背景图阴影的像素位置。
- 代码在Github上：https://github.com/pagewang0/qq_helper

### 手游自动登录脚本（android）
- 使用uiautomator来操作app启动、退出，实现批量登录功能
- 在此期间还尝试反编译手游的部分java代码，涉及登录逻辑。
- 尝试过java到smali语言转换，以及重新打包app。

## 总结
- 熟悉后端开发，使用node.js编写resfulAPI, 使用过Mongodb、Redis, 手写过Sql(Mysql、SQL Server、PostgreSQL)，也用过ORM框架（Sequelize/Mongoose）。
- 熟悉前端开发，编写过后台管理系统，能熟练操作DOM、BOM，曾使用过React+Flux写过spa，了解过Angular。
- 代码规范方面，接触过eslint, 工作中使用过git flow和code reivew(通过gitlab merge request)。
- 编写测试用例(行为测试和单元测试)，接触过gitlab CI/CD 以及docker。
- 略懂python，写过爬虫（主要是python工具库比较多且易用）。
- 使用Mac开发环境，在外网部署过服务。配过Nginx代理、域名解析。
- 对web安全(xss, csrf)、sql注入有所了解。
