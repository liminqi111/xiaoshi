# xiaoshi

#### 介绍
这是一款既可以下单又可以接单的外卖跑腿的小程序，用户既可以下单让别人帮忙带物品，又可以接单帮别人带物品。

#### 项目设计文档

介绍：微信小程序每个页面的具体样式及该页面对应的代码位置已经在设计文档中详细介绍，如有需要，可基于此对项目进行改造和完善。

文档路径：https://gitee.com/woody-cloud-shadow/xiaoshi/blob/master/%E5%B0%8F%E5%B8%82%E9%A1%B9%E7%9B%AE%E8%AE%BE%E8%AE%A1%E6%96%87%E6%A1%A3.docx



#### 技术选型

 **前端小程序** ：iView、colorUI、vant三个页面框架

 **后端接口** 基于springboot,且项目部署在微信云托管，因为微信小程序接口调用会存在合法域名校验，微信云托管可以绕过这个域名校验，调用云托管自己的内部接口。
前端文档参考链接：

 **iView** :http://inmap.talkingdata.com/wx/index_prod.html#/docs/guide/start

 **colorUI** :http://events.jianshu.io/p/60b0a0cb3f89

 **vant** :https://vant-contrib.gitee.io/vant-weapp/#/home

#### 前端样式

本处仅列出首页三个tab页面的样式，目前比较简单，但是功能齐全，后续将逐渐完善其功能。如果想查看其它页面样式，需下载小程序代码部署查看。获取联系我申请小程序体验权限。联系方式在最下面的一级菜单。

1.  首页

![输入图片说明](image.png)

2.  去接单

![输入图片说明](image1.png)

3.  我的

![输入图片说明](image2.png)

#### 代码部署使用说明

1.  下载仓库小程序代码，找到app.js文件，修改globalData的这三个参数【m_AppId，m_mi，resourceEnv】即可。

m_AppId：就是你的小程序ID

m_mi：即小程序密钥

查看位置：登录微信公众平台，开发——》开发管理——》开发设置

![输入图片说明](imageappid.png)

resourceEnv:即你的云托管服务ID

查看位置：登录微信云托管，服务管理——》服务列表

![输入图片说明](imageenv.png)

2.  云托管开通链接：https://cloud.weixin.qq.com/cloudrun

3.  云托管部署spring-boot项目，项目部署参考文档链接https://developers.weixin.qq.com/miniprogram/dev/wxcloudrun/src/development/storage/miniapp/delete.html。开发不易，后台spring-boot项目并未在仓库提供，可联系我微信获取项目源码及sql建表语句。

4.  下单类别目前仅有饮品类，您可以基于代码继续完善其它类别，我本人后续也会继续完善。

#### 参与贡献

1.  木心云影


#### 联系方式

1.  我的微信
![输入图片说明](ec11964ce3f13937fc8c5122e3263aa.jpg)
2.  我的QQ
1909531623

