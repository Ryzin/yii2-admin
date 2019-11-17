# Yii-admin 是使用Yii2开发的一个后台管理系统

## 2019-11-17
* 覆盖了Yii2的高级模板
* 主要添加了Yii2高级模板中的vendor/，保留了bower-asset/，改为bower/
* 注释了backend/config/main.php中apche get version
* 创建了storage/assets/
* 替换了db的账号密码

<br/>
<br/>

## 现可正常启动
* 后台页面路径为：根目录/admin.php

<br/>
<br/>

## 环境：
* phpstudy 8.0.9.3
* Apache 2.4.39
* MySQL 5.7.26
* php 7.3.4

<br/>
<br/>

## 以下为原说明：

主要功能：RBAC

安装:     
	1、下载源文件或git clone https://github.com/qiaohongbo/yii2-admin.git     
	2、composer install     
	3、common/config/main.php #配置数据库      
	4、Nginx和Apache配置，并设置hosts文件     
	数据库文件：yii2-admin.sql     
	管理员账号：admin     
	管理员密码：123456     
	
预览：
![image](https://github.com/qiaohongbo/yii2-admin/blob/master/statics/images/01.png)
![image](https://github.com/qiaohongbo/yii2-admin/blob/master/statics/images/02.png)
![image](https://github.com/qiaohongbo/yii2-admin/blob/master/statics/images/03.png)
![image](https://github.com/qiaohongbo/yii2-admin/blob/master/statics/images/04.png)
![image](https://github.com/qiaohongbo/yii2-admin/blob/master/statics/images/05.png)
