# OUC-autoLogin
利用IOS快捷指令+自动化实现OUC校园网自动登录



## 前言

你还在因为IOS每次息屏就断开校园网而感到烦恼吗？你还在因为每次脸上OUC-AUTO之后还有等几秒钟才弹出来登录界面而苦苦等待嘛？你还在每次都有点登录界面再验证指纹而感到麻烦嘛？

现在有了更好的选择，使用快捷指令+自动化解放双手。从此开始便捷地享受40兆飞驰人生。



## 下载方式

方法一：[点击下载](https://www.icloud.com/shortcuts/17c3642365024feab55464f7b3ea8549)

方法二：下载仓库中的`.shortcut`文件



## 使用方法

### 快捷指令

添加到快捷指令中心之后，还需要配置两个参数：`user_account`和`user_password`，学号和校园网密码

打开`快捷指令` 点击 刚刚添加地快捷指令右上角的三个点：

<img src="https://cdn.lmark.cc/img/e02e9eaeda404f0266781074646c9d6.jpg" alt="e02e9eaeda404f0266781074646c9d6" style="zoom:67%;" />

分别填入自己的学号和校园网密码（默认身份证后六位）

学号:

<img src="https://cdn.lmark.cc/img/image-20240502165135514.png" alt="image-20240502165135514" style="zoom:80%;" />

校园网密码：

<img src="https://cdn.lmark.cc/img/image-20240502165243323.png" alt="image-20240502165243323" style="zoom:80%;" />

配置完成即可使用，此时只要连接上OUC-AUTO或OUC-WIFI之后，再运行快捷指令即可自动登录

![image-20240502165517743](https://cdn.lmark.cc/img/image-20240502165517743.png)

如果你点一下OUC-AUTO就跳转到登录界面，可以在WIFI设置了关闭`自动登录`。

<img src="https://cdn.lmark.cc/img/a6cb7b33b91a6161d353f94e103fe7d.jpg" alt="a6cb7b33b91a6161d353f94e103fe7d" style="zoom:67%;" />





## 自动化设置（可选）

上述快捷指令还需要在连接上wifi后手动运行，还不够自动化，搭配自动化场景可以做到打开wifi后自动连接AUTO并登录。

打开`快捷指令`，选择`自动化`，选择`新建自动化`或点击`+`，选择`无线局域网`

<img src="https://cdn.lmark.cc/img/86344a248d880a2945bf0201a756a06.jpg" alt="86344a248d880a2945bf0201a756a06" style="zoom:67%;" />

在条件设置界面分别选择`网络`:OUC-AUTO或OUC-WIFI

并且勾选`连接中断后运行`

勾选`立即运行`

<img src="https://cdn.lmark.cc/img/08a50a9cf9d2cebd57d3c0ea3a6dd40.jpg" alt="08a50a9cf9d2cebd57d3c0ea3a6dd40" style="zoom:67%;" />

然后在动作选择界面选择刚刚添加的快捷指令：

![image-20240502171215852](https://cdn.lmark.cc/img/image-20240502171215852.png)

至此，配置基本完成了，如果想一打开WIFI就自动连接，可以把OUC-AUTO的WIFI设置里的`自动加入`打开





## 常见问题

- 快捷指令第一次运行提示各种权限，全部勾选`始终允许`即可
- 有时候如果打开了OUC-AUTO的自动登录，在运行快捷指令时可能会提示`目前数据连接不可用`，可以试试关闭`自动登录`，并重新打开WIFI



