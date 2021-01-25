# 随手拍/事件上传平台
本平台分为PC和移动端，PC端为管理后台，可以查看事件进度，管理上下级机构，工作量统计，与管理APP轮播图，公告通知，短信与推送开关。移动端主要分为3端，分别为普通用户端，管理端，单位端。其中管理端，单位端拥有普通用户的全部功能。用户端主要是上传事件，显示上传列表。管理端主要对用户上传的事件审核，下发单位端进行处理。单位端主要对下发的时间进行处理。内含即时聊天，可以单聊，群聊。可以发文字，图片，文件。

## 技术选型
### 1、环境
Java SDK 8
Apache Maven 3.6+
### 2、主框架
Spring Boot 2.0
Beetl模板
Mybatis
Shiro
Redis/ehcache
### 3、存储
数据库：Mysql

## 功能介绍
### 管理后台
平台全局设置，控制短信，移动端	推送等全局配置，修改配置无需停服务。
