Name: wangcong

Email: pagewang0@gmail.com

## Education

Hubei Polytechnic Institute(Computer Application Technology) Sep.2010 - Jun.2013

## Introduce

- Familiar with backend development, proficient in writing RESTful APIs using node.js, experienced in using Mongodb (mongoose) and Redis, have hand-coded SQL, and also have experience with ORM (Sequelize).

- Proficient in frontend development, have developed backend management systems, can manipulate DOM and BOM.

- Can write test cases (functional tests and unit tests), have experience in deployment, writing gitlab CI/CD and Dockerfile, Docker Compose.

- Have a certain understanding of web security (xss, csrf) and SQL injection.

- Recent time, I have learn AWS(lambda, ec2, dynamodb, s3, iam).

## Work Experience

#### Dreamwalk Technologies Limited (remote) Mar.2022 - Aug.2022

- Responsible for the back-end development of the e-commerce project "Masion Waster 2.0" (http://masionwester.vip), involving modifications to refund (Alipay/WeChat) and return-refund processes.

- Responsible for the back-end development of an NFT music website project, involving live broadcasting (Agora), web crawling (OpenSea), and WebSocket development.

#### Shanghai BuEn Technology Co., Ltd. Mar.2021 - May.2022

- Responsible for community project development using node.js, based on the open source project rocket.chat(https://github.com/RocketChat/Rocket.Chat) with further development.

- Integration of OAuth service.

- Integration of chat bot (hubot).

- Setting up gitlab CI/CD for running automated tests and deployments (build, test, deploy).

- Setting up kibana for log viewing.

- Writing shell scripts for project deployment.

- Using Vue to build the backend administration page.

- In situations where modifying code, compiling and running the project is time-consuming, unit tests are used to improve the compiling and running speed of some code and increase development efficiency.

#### Longkang Mdt InfoTech Ltd. Sep.2019 - Mar.2020

- Node.js backend development, using the WebSocket protocol, based on Socket.io(https://github.com/socketio/socket.io).

- Providing message push service for other services and access service and coordination connection strategies for clients (Web, Android, IOS, Windows).

- Troubleshooting memory leaks in the project.

- Stress testing: There are certain requirements for project performance and stability. After completing the functionality, the project is subjected to stress testing, which involves writing stress testing scripts to simulate CPU and memory conditions under multi-user scenarios.

#### Shenzhen Derkee Information Technology Co., Ltd. Dec.2017 - Nov.2018

- Mainly responsible for back-end development of the online financial management shop.

- Involves shop opening reviews, shelf management, simulated portfolio, performance optimization, scheduled tasks, and message push notifications.

## Project Experience

#### Masion Wester

- Fix for issues with Alipay/WeChat refunds.

- Order refund process.

#### Music-related NFT project

- Use Puppeteer to scrape music-related NFT data on OpenSea.

- Integrate with Agora for live streaming functionality.

- Implement WebSocket one-on-one chat feature.

#### Community project

- This project uses the meteor.js framework and MongoDB for storage.

- As for the chatbot, the functionality of human assistance has been extended.

- Several new feature modules have been added, such as custom emoji management, post (graphic and text), post secondary reply, message notifications, and permission role management.

- ActiveMQ is used for communication with other back-end services of the company, such as lottery activities.

#### ESG Public Opinion Early Warning(SaaS)

- Using the Koa framework and MySQL database.

- Features include user management, public opinion messages, stock filtering, investment portfolio management, message push, and data reporting.

- Resolving slow query issues in SQL.

#### Group Chat

- Use socket.io to build WebSocket communication.

- Koa provides HTTP services externally (mainly for cross-service communication and control of management terminals).

- Redis is used for data storage, and MySQL data is read-only.

- Use socket.io-redis for cross-service broadcasting communication.

#### Eshop

- The project architecture is based on microservices, and the database adopts a read-write separation approach with MongoDB. Redis is used for caching.

- OpenResty is used as the gateway.

- Redis is also utilized as a message queue to reduce the peak pressure caused by message push to the database.

#### Sliding CAPTCHA cracking

- Using the graphic processing capabilities of OpenCV and Selenium in Python, binary images are created for the background and sliding images. The color values of the sliding image are then reversed and pixel matching is performed to obtain the pixel positions of the sliding image and the background image's shadow.