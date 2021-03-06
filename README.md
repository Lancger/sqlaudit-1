<p align="center">
        <img width="300" src="logo.png">
</p>

# Yearning SQL审核平台

![](https://img.shields.io/badge/build-release-brightgreen.svg)  
![](https://img.shields.io/badge/version-v1.3.1-brightgreen.svg)  
![](https://img.shields.io/badge/vue.js-2.5.13-brightgreen.svg) 
![](https://img.shields.io/badge/iview-3.1.0-brightgreen.svg?style=flat-square) 
![](https://img.shields.io/badge/python-3.6-brightgreen.svg)
![](https://img.shields.io/badge/Django-2.0.1-brightgreen.svg)

##### 企业级MYSQL web端 SQL审核平台。

# 附加说明： 本人基于yearning二次开发，增加soara优化功能，主要更改了前端菜单权限认证，后端增加soar优化结果返回功能

## Feature 功能

- 数据库字典自动生成
- SQL查询
    - 查询工单 
    - 导出
    - soar优化
    - 自动补全，智能提示 
    - 查询语句审计
- SQL可视化自动生成
    - 索引语句自动生成
    - DDL语句自动生成
- SQL审核
    - 流程化工单
    - SQL语句检测与执行
    - SQL回滚
    - 历史审核记录
- 推送
    - E-mail工单推送
    - 钉钉webhook机器人工单推送
- 其他
    - todoList
    - LDAP登陆  
    - 动态配置 
- 用户权限及管理
    - 拼图式权限划分(共12项独立权限,可随意组合)
    - 组合式权限组
    - 支持限制邮箱后缀名的有限注册功能

## Environment 环境

- Python 3.6

- Vue.js 2.5

- Django 2.0

## Install 安装及使用日志
## soar下载地址，请放置在/usr/local/Yearning文件夹下面
wget https://github.com/XiaoMi/soar/releases/download/v0.8.0/soar.linux-amd64 -O soar
chmod a+x soar

[使用及安装文档](http://supermancookie.com/Yearning-document/)


  
## About 联系方式
   
   QQ:570126829
   
   E-mail: 570126829@qq.com

## Snapshot 效果展示

- Login



![login](http://oy0f4k5qi.bkt.clouddn.com/687474703a2f2f6f793066346b3571692e626b742e636c6f7564646e2e636f6d2f6c6f67696e2e706e67.jpeg)


- Dashboard

![](http://oy0f4k5qi.bkt.clouddn.com/dash.png)

- 审核

![](http://oy0f4k5qi.bkt.clouddn.com/order.png)

- SQL语法高亮及自动补全

![](http://oy0f4k5qi.bkt.clouddn.com/lighit.png)

- 查询

![](http://oy0f4k5qi.bkt.clouddn.com/query.png)

- 细粒度的权限分配
![](http://oy0f4k5qi.bkt.clouddn.com/PER.png)

- 我的工单
![](http://oy0f4k5qi.bkt.clouddn.com/myorder.png)


## License

- AGPL v3

任何二次开发及二次开源项目请严格遵守相应开源许可

2018 © Cookie


