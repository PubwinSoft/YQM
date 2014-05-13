<<<<<<< HEAD
## 使用说明 ##

呃，这是一款简单的邀请码系统，由麦田一根葱([www.yuxiaoxi.com][1])编写。

可以轻松的在后台管理生成邀请码，生成的邀请码只能使用一次，验证信息是通过session存储在本地的，只要没删除，就不用重复验证。

在后台，已使用的邀请码会以删除线表示。

## 文件说明 ##

 1. admin.php 管理登录 
 2. changepwd.php 修改管理密码 
 3. conn.php 数据库配置 
 4. going.php 邀请码验证
 5. index.php 首页 
 6. login.php 邀请码验证通过后跳转到的页面（根据需要自定决定，在going.php第23行）
 7. loginout.php 退出登录 
 8. yaoqingma.php 邀请码生成页 
 9. xxxx.sql 数据库文件 
 10. css 层叠样式表存放位置
 11. img 图片存放位置

## 自定义邀请码 ##

自定义邀请码位数：用代码编辑器打开`yaoqingma.php`，找到第42行的`$password_length = 10`，修改`10`为你需要的数字。
自定义邀请码组成：本系统邀请码默认是由`abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789`随机组成的，可以根据需要进行修改。在`yaoqingma.php`第`43`行。

## 安装说明 ##

请先打开`conn.php`修改数据库配置，然后引入数据库：`xxxx.sql`。

 - 默认管理帐号：admin 
 - 默认管理密码：admin 
 - 默认登录码：12345 
 - 默认邀请码：yaoqingma

如在使用过程中遇到任何问题，请登录作者网站： [http://www.yuxiaoxi.com/2013-07-04-yaoqingma.html][2] 提交您的问题


  [1]: http://www.yuxiaoxi.com/2013-07-04-yaoqingma.html
  [2]: http://www.yuxiaoxi.com/2013-07-04-yaoqingma.html
=======
yaogingma
=========

这是一款简单的邀请码系统，由麦田一根葱(www.yuxiaoxi.com)编写。可以轻松的在后台管理生成邀请码，生成的邀请码只能使用一次，验证信息是通过session存储在本地的，只要没删除，就不用重复验证。
>>>>>>> f2e6f2f2344fc2840190d360271e5e75e775d351
