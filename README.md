# 001jsp+servlet高校社团管理系统

### 简介
高校社团管理系统分为前后台，角色分为三种：管理员、社长、普通社员。

超级管理员角色包含以下功能：会员管理,物品管理,活动审批,系统用户管理,社团添加删除等功能。

社长角色包含以下功能：社团管理员登录,会员管理,物品管理,活动管理,查询社团信息,密码修改等功能。

普通社员角色包含以下功能：社员登录,申请入社,物品查看,活动申请等功能。

前台主要是展示社团列表、社团风采、社团活动、新闻列表
前台登录后进入个人中心，在个人中心能申请加入社团、查看参加的社团活动等
后台为管理员与社长使用，应用于对社团的管理及内容发布等。

源码获取：[ **点此获取** ](http://www.shuyue.fun/?type=productinfo&id=76)
演示视频：[ **点此查看** ](https://www.bilibili.com/video/BV1xf4y1a7XC/)

### 环境需要
````
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目
6.数据库：MySql 8.0版本；
````
### 使用技术
使用技术：servlet+jsp+mysql 8.0

### 数据库配置
数据库使用mysql 8.0,注意版本要匹配，否则可能会产生连接异常的情况，导入sql文件team.sql.导入成功后，在db.properties中修改数据库相关配置

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/183335_6a999919_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/183405_2f6fa710_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/183413_5f92414b_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/183421_20352d14_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/183430_fb84b876_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/183440_83ed2f87_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/183448_12152bda_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/183455_c3e591da_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/183505_2d13aa20_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/183514_0fbf7ed0_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/183523_e5d63aab_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/183532_ceb77819_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/183540_fdb2704f_863230.png "屏幕截图.png")
