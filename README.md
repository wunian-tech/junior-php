## 五念技术部初级PHP程序员测试题

    下面测试任选其一，完成之后可以用你的github或bitbucket仓库分享给我们(尤佳)，或把代码及数据库发送到maggiezh@wuniansy.com。

### TEST 1
---
#### 内容描述

    - 使用你熟悉的框架做一个简单的Blog。
    - 用户类别分为Guest和登陆用户。
    - 登陆用户可以发布博客，修改博客，删除博客（软删除），博客浏览权限不限制。
    - 登陆用户之间可以相互评论。做成百度贴吧的回复模式即可，无限极尤佳。
    - 登陆用户之间可以相互关注。
    - 用户可以发布自己的动态（类似微信），有图片有文字，只有关注用户可以看到彼此的动态。
    - 用户可以管理自己的动态（CURD）。

    * 要求使用PHP+Apache/Nginx+MySql(版本不限)
    * 框架要求Laravel, TP5.0，<b>不可以使用cms</b>
    * 合理设计数据库
    * 前端界面干净整洁即可

#### 文档链接

- [laravel官网](https://laravel.com/)
- [TP5.0手册](https://www.kancloud.cn/manual/thinkphp5)

### TEST 3
---
#### 内容描述

    - 使用<b>Laravel5+版本</b>框架完成以下需求
    - 在laravel默认的users migrate基础上，完善或添加以下内容（链表不限制，但要合理设计）：

        - 用户名
        - 密码
        - 性别(radio)
        - 手机号（唯一索引）
        - 邮箱

    - 创建用户模块，可以使用Laravel Auth完成用户登录，注册，找回密码，但我们设置为手机号为唯一索引。
    - 用户可以可以编辑修改自己的资料，上传头像。
    - 使用composer安装一个admin cms，可以管理前台用户的信息即可。

    * 要求使用PHP+Apache/Nginx+MySql(版本不限)
    * 框架要求Laravel
    * 合理设计数据库，使用migration做脚本迁移
    * 完整的说明文档README.md
    * 注意gitignore
    * 前端界面干净整洁即可

#### 文档链接

- [laravel官网](https://laravel.com/)
- [laravel服务 - 用户认证](http://laravelacademy.org/post/3074.html)
- [laravel HTTP控制器实例教程 - 创建RESTFul风格控制器实现文章增删改查](http://laravelacademy.org/post/549.html)
