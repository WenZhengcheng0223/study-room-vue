
## 原框架地址：[RuoYi-Vue-Plus: 后台管理系统 重写RuoYi-Vue所有功能 集成 Sa-Token+Mybatis-Plus+Jackson+Xxl-Job+knife4j+Hutool+OSS 定期同步 (gitee.com)](https://gitee.com/JavaLionLi/RuoYi-Vue-Plus)
#### 在其基础上增加了一些微信小程序相关的接口功能作为自习室预约平台小程序的后端，微信相关接口参考：[Wechat-Group/WxJava: 微信开发 Java SDK ，支持包括微信支付，开放平台，小程序，企业微信，公众号等的后端开发 (github.com)](https://github.com/Wechat-Group/WxJava)
#### 自习室预约平台微信小程序：[自习室预约平台微信小程序](https://gitee.com/zmn_repository/wx-study-room)

## 平台简介

> RuoYi-Vue-Plus 是重写 RuoYi-Vue 针对 `分布式集群` 场景全方位升级(不兼容原框架)

> 系统演示: [传送门](https://gitee.com/JavaLionLi/RuoYi-Vue-Plus/wikis/系统演示?sort_id=4836388)

| 功能介绍     | 使用技术                | 文档地址                                                                                              | 特性注意事项                     |
|----------|---------------------|---------------------------------------------------------------------------------------------------|----------------------------|
| 当前框架     | RuoYi-Vue-Plus      | [RuoYi-Vue-Plus文档](https://gitee.com/JavaLionLi/RuoYi-Vue-Plus/wikis/pages)                       | 重写RuoYi-Vue全方位升级(不兼容原框架)   |
| 微服务分支    | RuoYi-Cloud-Plus    | [微服务分支地址](https://gitee.com/JavaLionLi/RuoYi-Cloud-Plus)                                          | 重写RuoYi-Cloud全方位升级(不兼容原框架) |
| 单体分支     | RuoYi-Vue-Plus-fast | [fast分支地址](https://gitee.com/JavaLionLi/RuoYi-Vue-Plus/tree/fast/)                                | 单体应用结构                     |
| Vue3分支   | RuoYi-Vue-Plus-UI   | [UI地址](https://gitee.com/JavaLionLi/RuoYi-Vue-Plus-UI)                                            | 由于组件还未完善 仅供学习              |
| 原框架      | RuoYi-Vue           | [RuoYi-Vue官网](http://ruoyi.vip/)                                                                  | 定期同步需要的功能                  |
| 前端开发框架   | Vue、Element UI      | [Element UI官网](https://element.eleme.cn/#/zh-CN)                                                  |                            |
| 后端开发框架   | SpringBoot          | [SpringBoot官网](https://spring.io/projects/spring-boot/#learn)                                     |                            |
| 容器框架     | Undertow            | [Undertow官网](https://undertow.io/)                                                                | 基于 XNIO 的高性能容器             |
| 权限认证框架   | Sa-Token、Jwt        | [Sa-Token官网](https://sa-token.dev33.cn/)                                                          | 强解耦、强扩展                    |
| 关系数据库    | MySQL               | [MySQL官网](https://dev.mysql.com/)                                                                 | 适配 8.X 最低 5.7              |
| 关系数据库    | Oracle              | [Oracle官网](https://www.oracle.com/cn/database/)                                                   | 适配 11g 12c                 |
| 关系数据库    | PostgreSQL          | [PostgreSQL官网](https://www.postgresql.org/)                                                       | 适配 13 14                   |
| 关系数据库    | SQLServer           | [SQLServer官网](https://docs.microsoft.com/zh-cn/sql/sql-server)                                    | 适配 2017 2019               |
| 缓存数据库    | Redis               | [Redis官网](https://redis.io/)                                                                      | 适配 6.X 最低 4.X              |
| 数据库框架    | Mybatis-Plus        | [Mybatis-Plus文档](https://baomidou.com/guide/)                                                     | 快速 CRUD 增加开发效率             |
| 数据库框架    | p6spy               | [p6spy官网](https://p6spy.readthedocs.io/)                                                          | 更强劲的 SQL 分析                |
| 多数据源框架   | dynamic-datasource  | [dynamic-ds文档](https://www.kancloud.cn/tracy5546/dynamic-datasource/content)                      | 支持主从与多种类数据库异构              |
| 序列化框架    | Jackson             | [Jackson官网](https://github.com/FasterXML/jackson)                                                 | 统一使用 jackson 高效可靠          |
| Redis客户端 | Redisson            | [Redisson文档](https://github.com/redisson/redisson/wiki/%E7%9B%AE%E5%BD%95)                        | 支持单机、集群配置                  |
| 分布式限流    | Redisson            | [Redisson文档](https://github.com/redisson/redisson/wiki/%E7%9B%AE%E5%BD%95)                        | 全局、请求IP、集群ID 多种限流          |
| 分布式队列    | Redisson            | [Redisson文档](https://github.com/redisson/redisson/wiki/%E7%9B%AE%E5%BD%95)                        | 普通队列、延迟队列、优先队列 等           |
| 分布式锁     | Lock4j              | [Lock4j官网](https://gitee.com/baomidou/lock4j)                                                     | 注解锁、工具锁 多种多样               |
| 分布式幂等    | Redisson            | [Lock4j文档](https://gitee.com/baomidou/lock4j)                                                     | 拦截重复提交                     |
| 分布式日志    | TLog                | [TLog文档](https://yomahub.com/tlog/docs)                                                           | 支持跟踪链路日志记录、性能分析、链路排查       |
| 分布式任务调度  | Xxl-Job             | [Xxl-Job官网](https://www.xuxueli.com/xxl-job/)                                                     | 高性能 高可靠 易扩展                |
| 文件存储     | Minio               | [Minio文档](https://docs.min.io/)                                                                   | 本地存储                       |
| 文件存储     | 七牛、阿里、腾讯            | [OSS使用文档](https://gitee.com/JavaLionLi/RuoYi-Vue-Plus/wikis/pages?sort_id=4359146&doc_id=1469725) | 云存储                        |
| 监控框架     | SpringBoot-Admin    | [SpringBoot-Admin文档](https://codecentric.github.io/spring-boot-admin/current/)                    | 全方位服务监控                    |
| 校验框架     | Validation          | [Validation文档](https://docs.jboss.org/hibernate/stable/validator/reference/en-US/html_single/)    | 增强接口安全性、严谨性 支持国际化          |
| Excel框架  | Alibaba EasyExcel   | [EasyExcel文档](https://www.yuque.com/easyexcel/doc/easyexcel)                                      | 性能优异 扩展性强                  |
| 文档框架     | Knife4j             | [Knife4j文档](https://doc.xiaominfo.com/knife4j/documentation/)                                     | 美化接口文档                     |
| 工具类框架    | Hutool、Lombok       | [Hutool文档](https://www.hutool.cn/docs/)                                                           | 减少代码冗余 增加安全性               |
| 代码生成器    | 适配MP、Knife4j规范化代码   | [Hutool文档](https://www.hutool.cn/docs/)                                                           | 一键生成前后端代码                  |
| 部署方式     | Docker              | [Docker文档](https://docs.docker.com/)                                                              | 容器编排 一键部署业务集群              |
| 国际化      | SpringMessage       | [SpringMVC文档](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html#mvc)   | Spring标准国际化方案              |

## 参考文档

使用框架前请仔细阅读文档重点注意事项
<br>
>[初始化项目 必看](https://gitee.com/JavaLionLi/RuoYi-Vue-Plus/wikis/关于初始化项目?sort_id=4164117)
>>[https://gitee.com/JavaLionLi/RuoYi-Vue-Plus/wikis/关于初始化项目?sort_id=4164117](https://gitee.com/JavaLionLi/RuoYi-Vue-Plus/wikis/关于初始化项目?sort_id=4164117)
> 
>[部署项目 必看](https://gitee.com/JavaLionLi/RuoYi-Vue-Plus/wikis/关于应用部署?sort_id=4219382)
>>[https://gitee.com/JavaLionLi/RuoYi-Vue-Plus/wikis/关于应用部署?sort_id=4219382](https://gitee.com/JavaLionLi/RuoYi-Vue-Plus/wikis/关于应用部署?sort_id=4219382)
> 
>[参考文档 Wiki](https://gitee.com/JavaLionLi/RuoYi-Vue-Plus/wikis/pages)
>>[https://gitee.com/JavaLionLi/RuoYi-Vue-Plus/wikis/pages](https://gitee.com/JavaLionLi/RuoYi-Vue-Plus/wikis/pages)

## 软件架构图

![Plus部署架构图](https://images.gitee.com/uploads/images/2021/1112/202137_673ac5d2_1766278.png "Plus部署架构图.png")
## 贡献代码

欢迎各路英雄豪杰 `PR` 代码 请提交到 `dev` 开发分支 统一测试发版

框架定位为 `通用后台管理系统(分布式集群强化)` 原则上不接受业务 `PR`

### 其他

* 同步升级 RuoYi-Vue

* GitHub 地址 [RuoYi-Vue-Plus-github](https://github.com/JavaLionLi/RuoYi-Vue-Plus)

* 单模块 分支 [RuoYi-Vue-Plus-fast](https://gitee.com/JavaLionLi/RuoYi-Vue-Plus/tree/fast/)

* 微服务 分支 [RuoYi-Cloud-Plus](https://gitee.com/JavaLionLi/RuoYi-Cloud-Plus)

* 用户扩展项目 [扩展项目列表](https://gitee.com/JavaLionLi/RuoYi-Vue-Plus/wikis/pages?sort_id=4478302&doc_id=1469725)

  

## 业务功能

| 功能 | 介绍 |
|---|---|
| 用户管理 | 用户是系统操作者，该功能主要完成系统用户配置。 |
| 部门管理 | 配置系统组织机构（公司、部门、小组），树结构展现支持数据权限。 |
| 岗位管理 | 配置系统用户所属担任职务。 |
| 菜单管理 | 配置系统菜单，操作权限，按钮权限标识等。 |
| 角色管理 | 角色菜单权限分配、设置角色按机构进行数据范围权限划分。 |
| 字典管理 | 对系统中经常使用的一些较为固定的数据进行维护。 |
| 参数管理 | 对系统动态配置常用参数。 |
| 通知公告 | 系统通知公告信息发布维护。 |
| 操作日志 | 系统正常操作日志记录和查询；系统异常信息日志记录和查询。 |
| 登录日志 | 系统登录日志记录查询包含登录异常。 |
| 文件管理 | 系统文件上传、下载等管理。 |
| 定时任务 | 在线（添加、修改、删除)任务调度包含执行结果日志。 |
| 代码生成 | 前后端代码的生成（java、html、xml、sql）支持CRUD下载 。 |
| 系统接口 | 根据业务代码自动生成相关的api接口文档。 |
| 服务监控 | 监视集群系统CPU、内存、磁盘、堆栈、在线日志、Spring相关配置等。 |
| 缓存监控 | 对系统的缓存信息查询，命令统计等。 |
| 在线构建器 | 拖动表单元素生成相应的HTML代码。 |
| 连接池监视 | 监视当前系统数据库连接池状态，可进行分析SQL找出系统性能瓶颈。 |
| 使用案例 | 系统的一些功能案例 |



