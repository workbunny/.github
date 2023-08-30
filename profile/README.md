<!--<p align="center"><img width="150px" src="https://chaz6chez.cn/images/workbunny-logo.png" alt="workbunny"></p>-->

## 🐰 Workbunny Group
Workbunny小组是一个活跃的爱折腾的开发小组，我们相信在一定约束下的重复制造轮子可以带来新的创新或者是新的思考；
目前主要围绕PHP-cli进行开发，包括开发一些可以直接投入使用的服务程序、一些可以即插即用的composer组件以及一些围绕webman生态的插件；
未来我们会进行一些其它语言的探索，比如Rust、Python，但始终希望未来PHP的开发环境会更好。

- 轻量的PHP多进程助手库 [workbunny/process](https://github.com/workbunny/process) | 对pcntl_fork()的极简化封装，让多进程更简单易懂
- 基于事件驱动拓展的PHP高性能轻量级事件循环库 [workbunny/event-loop](https://github.com/workbunny/event-loop) | 比较好的event-loop教学用库，包含较完善的测试用例

## 🐰 Webman Plugins
以下是一些长期维护的Webman生态插件，均在生产环境下得到至少半年以上时间的验证：

- Webman的Nacos客户端插件 [workbunny/webman-nacos](https://github.com/workbunny/webman-nacos) | **LTS** | [项目计划](https://github.com/orgs/workbunny/projects/5)
- Webman的RabbitMQ客户端插件 [workbunny/webman-rabbitmq](https://github.com/workbunny/webman-rabbitmq) | **LTS** | [项目计划](https://github.com/orgs/workbunny/projects/4)
  - 1.x 长期支持
  - 2.0.0-beta.x 持续跟进……
- Webman的Redis-Stream轻量级队列插件 [workbunny/webman-rqueue](https://github.com/workbunny/webman-rqueue) | **LTS** | [项目计划](https://github.com/orgs/workbunny/projects/3) 
  - 1.x **预计2024年Q1放弃维护，建议升级至2.x**
  - 2.x 长期支持
- Webman的即时通讯服务端插件 [workbunny/webman-push-server](https://github.com/workbunny/webman-push-server) | **LTS** | [项目计划](https://github.com/orgs/workbunny/projects/6)
  - 1.x 长期支持
- Webman的高速共享缓存插件 [workbunny/webman-shared-cache](https://github.com/workbunny/webman-shared-cache) | **LTS** | [项目计划](https://github.com/orgs/workbunny/projects/9)
- Webman的IP本地库插件 [workbunny/webman-ip-attribution](https://github.com/workbunny/webman-ip-attribution) | **LTS** | 长期维护本地ip库（什么时候记起来了什么时候更新一下）


## 🐰 Experimental 
- 基于SQLite3的PHP储存驱动 [workbunny/storage](https://github.com/workbunny/storage)
- Webman的基于SQLite的限流插件 [workbunny/webman-rate-limiter](https://github.com/workbunny/webman--rate-limiter)
