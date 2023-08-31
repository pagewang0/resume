## 联系方式
Email: cGFnZXdhbmcwQGdtYWlsLmNvbQ==(base64)
微信: pagewang_cn

## 简介
- 熟悉后端开发，使用node.js编写resful API, 使用过Mongodb(mongoose)、Redis, 手写过Sql(接触过Mysql、SQL Server、PostgreSQL)，也用过ORM(Sequelize)。
- 熟悉前端开发，编写过后台管理系统，能操作DOM、BOM。
- 编写测试用例(行为测试和单元测试)，部署和编写过gitlab CI/CD以及dockerfile, Docker Compose。
- 对web安全(xss, csrf)、sql注入有一定的了解。

## 教育经历
湖北职业技术学院 大专 2010.9 - 2013.6

## 工作经验

### 梦猷科技 2022.5 - 2022.8 remote
- 负责电商项目[masion waster 2.0](http://masionwester.vip) 后端开发，涉及退款(支付宝/微信)，退货退款流程修改。
- 负责NFT音乐网站项目，后端开发，涉及直播(声网/agora)，爬虫(opensea), websocket开发。

### 部恩科技 2021.3 - 2022.5
- 负责社区项目node.js开发，基于开源项目rocket.chat做二次开发。
- 接入OAuth服务。
- 接入聊天机器人(hubot)。
- 搭建gitlab CI/CD跑自动化测试和部署(build、test、deploy)。
- 搭建kibana用于查看log。
- 编写shell脚本用于项目部署。
- 使用vue构建后台管理页面。
- 在项目修改代码编译运行比较费时的情况下，使用单元测试的方式来运行部分代码提升编译运行速度，提高开发效率。

### 隆康科技 2019.9 - 2020.3
- node.js后端开发，使用websocket协议，基于socket.io。
- 为其他服务提供消息推送，为客户端（Web、Android、IOS、Windows）提供接入服务和协调连接策略。
- 排查项目中的内存泄露问题。
- 压力测试，需求上对项目性能与稳定性有一定要求，在功能完备后，对项目进行压力测试，编写压测脚本，模拟多用户情况下的cpu、内存情况。

### 德科信息 2017.12 - 2018.11
- 主要负责理财网店后端开发。
- 涉及开店审核、货架、模拟组合、性能优化、定时任务、消息推送。

## 项目经验

### masion wester
- 支付宝/微信退款问题的修复。
- 订单退款流程。

### 音乐类NFT项目
- 使用puppeteer爬取opensea的音乐类NFT数据。
- 接入声网(agora)直播功能。
- websocket聊天(1对1)功能。


### steampy社区
- 项目使用meteor.js框架，存储使用mongodb。
- 在聊天机器人方面，扩展了人工客服功能。
- 扩展了一些新功能模块，例如自定义表情管理、帖子(图文)、帖子二级回复、消息提醒、权限角色管理等。
- 使用activeMQ来和公司其他后端服务做通信：比如抽奖活动。

### ESG舆情预警
- 使用koa框架，数据库使用mysql
- 功能涉及用户、舆情消息、股票筛选、投资组合、消息推送、数据报告。
- 解决sql中的慢查询问题。

### IM群聊服务
- 使用socket.io来构建websocket通信。
- koa对外提供http服务（主要是跨服务通信以及管理端控制）。
- 数据存储使用redis，mysql数据只读。
- 使用socket.io-redis来跨服务广播通信。

### 理财网店
- 项目结构是微服务，数据库使用mongodb读写分离，redis做缓存。
- 网关使用OpenResty。
- 使用redis做消息队列来消减消息推送给db带来的压力峰值。

### 滑动验证码破解
- 使用python中的selenium和openCV图形处理，针对背景图和滑动图做二值化，然后反转滑动图的色值，最后做像素匹配，得到滑动图与背景图阴影的像素位置。