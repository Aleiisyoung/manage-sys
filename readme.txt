开发环境：Eclipse+Tomcat7.0
开发框架：Spring+SpringMVC+Mybatis+Shiro
项目描述：该项目为企业公司的后台管理系统，主要包括：菜单管理、角色管理、组织管理、用户管理、日志管理、配置管理、系统权限管理（认证，授权），退出等，管理员用户通过登录身份认证后可依据权限增加、修改不同的角色，并记录日志信息。

个人负责：组织管理模块，数据的呈现和页面的增添、修改。
技术描述：
1.	使用Maven对项目进行分块管理
2.	使用Ztree控件实现角色权限树的管理，通过ajax异步动态添加、删除用户权限节点。
3.	使用Shiro安全框架验证登录
4.	使用AOP添加日志和事务的处理
