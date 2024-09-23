# 环境部署

本项目涉及三个部分：
- 后端服务：gin-blog-server
- 管理平台：gin-blog-admin
- 个人主页：gin-blog-front

1. 创建数据库：deploy/build/mysql/gvb.sql
2. 修改配置：gin-blog-server/config.yml
3. 登陆密码：

问题：
1. 登陆后会出现导航错误问题，需要手动指定路由！