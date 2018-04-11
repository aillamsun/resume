<img src="data/icon-resume.png" height="200"/>

---

## 联系方式
* 手机：13076061657（成都）
* Email：<1120sungang@gmail.com>
* QQ：1015905041
* Wechat：19911120

---

## 个人信息
* 孙刚 / 男 / 1991
* 工作 6年
* 勤智数码 / 研发中心 / 高级研发工程师
* 本科
* Github：<https://github.com/aillamsun/>
* 

* 期望职位：高级研发工程师,技术架构

---

## 技能清单
* Web开发：java / 熟悉jvm内存模型 / gc优化 / 多线程并发
* MVC框架：Spring mvc & Spring Boot
* Cache：Redis / memcache
* 单元测试：JUnit / Spring test / WebClient
* 前端：HTML / CSS / JS / jQuery库  
* 前端框架：Bootstrap / HTML5 / VUE
* 数据结构：数组 / 链表 / 堆栈&队列 / 红黑树 / Btree B+tree / 倒排索引
* 数据库相关：MySQL / Oracle / ElasticSearch
* 大数据相关：Hadoop spark大数据平台,编写mapreduce编程，能够使用hive sqoop fulme hbase zookeeper框架进行大数据分析计算，搭建Hadoop集群环境
* 版本管理：Git / SVN / nexus+maven进行项目构建，jenkins持续集成
* 其他：Ajax / SPL / cURL / WebSocket / Python / 敏捷项目开发 / 设计模式 / 正则表达式 / 性能优化及安全常识 / 内部标准编程风格
* 运维：熟练mysql主从复制 + keepalived 高可用集群架构
* 容器：熟练使用docker容器技术，docker cli操作
* 以Linux Mac作为日常操作系统 
* 坚持每日练习提高

---

## 个人作品

### [O2O实体门店三方接入管理系统](#)
- 项目名称：O2O实体门店三方接入管理系统
- 项目地址： 无
- 系统环境
  + Macos / intellij idea
- 技术栈
  + java / mysql / spring boot / mybatis	
- 简介
  + 主要是针对商城用户 对接京东到家，饿了么，美团外卖，商品自动上下架，同步价格，库存，统一处理订单确认，取消，退款，拣货，众包等操作，方便用户统一管理三方平台处理
- 责任描述
  + 搭建整个项目技术架构设计 ，全体功能只有我一人开发
  + 对三方提供api 统一封装处理，内部使用只需提供三方认证的三要素key通过spring boot统一注入配置
  + 提供统一开发api service接口封装
  + 开发所有平台业务场景，适配不通平台数据格式统一json转换


### [O2O商超连锁系统](#)
- 项目名称：O2O商超连锁系统
- 项目地址：[O2O商超连锁系统](http://mall.dehuichaoshi.com/)
- 系统环境
  + Macos / intellij idea
- 技术栈
  + java / mysql / spring boot / mybatis ／ elasticsearch / redis / rabbitmq	
- 简介
  + 结合线下实体门店，打通现在erp crm数据，提供线上用户会员绑定，卡券，活动等
  + 实现总店仓库统一商品管理，支持各门店商品自动上架，库存 价格 线下erp同步
  + 打通微信卡券功能
  + 供商城促销活动，秒杀，大并发缓存查询通过redis 实现
  + 实现LBS定位，根据当前位置  推荐给客户最近的门店
  + 系统通过批处理任务调度系统，周期实时同步线下超市门店 订单 库存 价格 资料的变更
  + 系统商品搜素，搜索记录通过elasticsearch 索引文档存储，通过mq 监听来修改索引数据同步
  + 系统提供 "圈子"功能，让商城用户，可以在圈子发表话题，查看资讯，评论，点赞等 
- 责任描述
  + 搭建整个项目技术架构设计，开发商品管理，订单管理，多店铺功能权限，数据权限隔离，开发类似兴趣部落功能 圈子
  + 商品检索，圈子 主题，资讯检索，使用elasticsearch文档索引
  + 搭建项目使用 redis elasticsearch集群 ，增加自动化部署jenkins 使用
  + 优化项目jvm 参数调优，mysql 性能优化，慢查询，索引优化
