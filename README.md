# New Online Judge（NOJ）

![logo](./logo.png)

[![Java](https://img.shields.io/badge/Java-1.8-informational)](http://openjdk.java.net/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.2.6.RELEASE-success)](https://spring.io/projects/spring-boot)
[![SpringCloud Alibaba](https://img.shields.io/badge/Spring%20Cloud%20Alibaba-2.2.1.RELEASE-success)](https://spring.io/projects/spring-cloud-alibaba)
[![MySQL](https://img.shields.io/badge/MySQL-8.0.19-blue)](https://www.mysql.com/)
[![Redis](https://img.shields.io/badge/Redis-5.0.9-red)](https://redis.io/)
[![Nacos](https://img.shields.io/badge/Nacos-1.4.2-%23267DF7)](https://github.com/alibaba/nacos)
[![Vue](https://img.shields.io/badge/Vue-2.6.11-success)](https://cn.vuejs.org/)

简体中文 | [English](./README-EN.md)

## 总概
  Powered by [HOJ](https://github.com/HimitZH/HOJ)
  
## 上线日记

| 时间         | 内容                                       | 更新者         |
| ---------- | ---------------------------------------- | ----------- |
| 2020-10-26 | 正式开发                                     | Himit_ZH    |
| 2021-04-10 | 首次上线测试                                   | Himit_ZH    |
| 2021-04-15 | 判题调度2.0解决并发问题                            | Himit_ZH    |
| 2021-04-16 | 重构解耦JudgeServer判题逻辑，添加部署文档               | Himit_ZH    |
| 2021-04-19 | 加入rsync实现评测数据同步，修复一些已知的BUG               | Himit_ZH    |
| 2021-04-24 | 加入题目模板，修改页面页脚                            | Himit_ZH    |
| 2021-05-02 | 修复比赛后管理员重判题目导致排行榜失效的问题                   | Himit_ZH    |
| 2021-05-09 | 添加公共讨论区，题目讨论区，比赛评论                       | Himit_ZH    |
| 2021-05-12 | 添加评论及回复删除，讨论举报，调整显示时间。                   | Himit_ZH    |
| 2021-05-16 | 完善权限控制，讨论管理员管理，讨论删除与编辑更新。                | Himit_ZH    |
| 2021-05-22 | 更新docker-compose一键部署，修正部分bug             | Himit_ZH    |
| 2021-05-24 | 判题调度乐观锁改为悲观锁                             | Himit_ZH    |
| 2021-05-28 | 增加导入导出题目，增加用户页面的最近登录，开发正式结束，进入维护摸鱼       | Himit_ZH    |
| 2021-06-02 | 大更新，完善补充前端页面，修正判题等待超时时间，修补一系列bug         | Himit_ZH    |
| 2021-06-07 | 修正特殊判题，增加前台i18n                          | Himit_ZH    |
| 2021-06-08 | 添加后台i18n,路由懒加载                           | Himit_ZH    |
| 2021-06-12 | 完善比赛赛制，具体请看在线文档                          | Himit_ZH    |
| 2021-06-14 | 完善后台管理员权限控制，恢复CF的vjudge判题                | Himit_ZH    |
| 2021-06-25 | 丰富前端操作，增加POJ的vjudge判题                    | Himit_ZH    |
| 2021-08-14 | 增加spj对使用testlib的支持                       | Himit_ZH    |
| 2021-09-21 | 增加比赛打印功能、账号限制功能                          | Himit_ZH    |
| 2021-10-05 | 增加站内消息系统——评论、回复、点赞、系统通知的消息，优化前端。         | Himit_ZH    |
| 2021-10-06 | 美化比赛排行榜，增加对FPS题目导入的支持                    | Himit_ZH    |
| 2021-12-09 | 美化比赛排行榜，增加外榜、打星队伍、关注队伍的支持                | Himit_ZH    |
| 2022-01-01 | 增加公开训练和公开训练（题单）                          | Himit_ZH    |
| 2022-01-04 | 增加交互判题、重构judgeserver的三种判题模式（普通、特殊、交互）    | Himit_ZH    |
| 2022-01-29 | 重构remote judge，增加AtCoder、SPOJ的支持         | Himit_ZH    |
| 2022-02-19 | 修改首页前端布局和题目列表页                           | Himit_ZH    |
| 2022-02-25 | 支持PyPy2、PyPy3、JavaScript V8、JavaScript Node、PHP | Himit_ZH    |
| 2022-03-12 | 后端接口全部重构，赛外榜单增加缓存                        | Himit_ZH    |
| 2022-03-28 | 合并冷蕴提交的团队功能                              | Himit_ZH、冷蕴 |
| 2022-04-01 | 正式上线团队功能                                 | Himit_ZH、冷蕴 |
| 2022-05-29 | 增加在线调试、个人主页提交热力图                         | Himit_ZH    |
| 2022-08-06 | 增加题目标签的分类管理（二级标签）                        | Himit_ZH    |
| 2022-08-21 | 增加人工评测、取消评测                              | Himit_ZH    |
| 2022-08-30 | 增加OI题目的subtask、ACM题目的'遇错止评'模式            | Himit_ZH    |
| 2022-10-04 | 增加比赛奖项配置，增加ACM赛制的滚榜                      | Himit_ZH    |
| 2022-11-14 | 增加题目详情页专注模式，优化首页布局                       | Himit_ZH    |
| 2023-05-01 | 增加题目评测支持文件IO                             | Himit_ZH    |
| 2023-05-03 | 更改图标、注册等一系列内容                             | Black.X    |
