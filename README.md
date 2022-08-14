> 本插件建议配合定制版typecho使用效果最佳

#### 适用版本 typecho1.1.17.10.30

- 其他版本需要修改插件文件夹目录下Plugin.php文件中的版本判断相关代码
![-1a37355e6ff8aefd.png][1]

## 功能说明
### 定制版Typecho可使用额外功能
- 找回密码请求时间间隔设置，防止恶意请求
![16421-0t2ifx44ct9g.png](https://www.xggm.top/usr/uploads/2022/08/1223188977.png)

- 找回密码功能，通过邮件找回密码
![71182-70ky04ujkz9.png](https://www.xggm.top/usr/uploads/2022/07/2992549955.png)
![68060-7cya78zrf83.png](https://www.xggm.top/usr/uploads/2022/08/3226386662.png)

- 评论审核通过时发送邮件给评论者
![20229-mzu3h5n83cp.png](https://www.xggm.top/usr/uploads/2022/07/1090835643.png)

- 用户评论文章时发送邮件给文章博主
![54051-xygr9m28zi.png](https://www.xggm.top/usr/uploads/2022/07/1330187515.png)

- 用户评论被回复时发送邮件给被评论用户
![97808-7rwi0jqvvuc.png](https://www.xggm.top/usr/uploads/2022/07/1054048011.png)


----------


## 邮件模板说明

插件有三个模板，可以根据自己的想法修改模板，在插件文件夹的`theme`目录下：

1. approved.html：邮件审核通过通知模板。

2. author.html：文章评论通知作者模板。

3. reply.html：评论回复通知被回复者模板。


----------


## 插件管理界面

![43417-t9c6zdaylr.png](https://www.xggm.top/usr/uploads/2022/08/3714260072.png)

![45112-jyqfcv098f.png](https://www.xggm.top/usr/uploads/2022/08/2321282562.png)


----------


  [1]: https://www.xggm.top/usr/uploads/2022/07/2779981298.png
