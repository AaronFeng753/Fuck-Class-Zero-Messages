# Fuck Class Zero Messages
教你禁用零级短信(霸屏短信or闪信)☠✉☠

大陆的运营商发的闪信也可以照样禁用!!!

#### 仅适用于已`ROOT`的`安卓`手机

# 欢迎转载本文,无需标注出处一类的,你当原创文章发我都没意见,能帮助到别人就好.

# 什么是霸屏短信?
一种直接霸占你的手机屏幕打断你当前在做的任何事情的恶心人的短信🤮

如图:

![0](/pics/0.jpg)

详细了解可以看[搜狐这篇文章](https://www.sohu.com/a/319817850_100113462)
# 如何禁用?

## 首先,你的手机得是安卓手机,已经获得root权限,并且最好是安卓原生系统.

如何root手机不在这里赘述,自己去搜索一下吧,不是很难,大致流程就是解锁,刷twrp,装面具.

### 1.先看看自己的短信app长啥样
笔者用的是安卓原生系统,所以短信app也是谷歌原生的message.

最好先确认一下自己的短信app是安卓原生的,如果不是原生的,我不保证该教程有用.

![1](/pics/1.png)

### 2.安装幸运破解器(Lucky~Patcher)
自己搜索找一个新版本的`幸运破解器`安装上,该给的权限都给了,`root权限`也得给他.

![2](/pics/2.png)

### 3.然后打开软件主界面,搜索找到`系统短信app`, 点击一下那一行会出现各种选项,选择`Menu of Patches`

![3](/pics/3.jpg)

### 4.选择`Remove Google ads`

![4](/pics/4.jpg)

### 5.选择`Disable ad activities`

![5](/pics/5.jpg)

### 6.在出现的菜单上方搜索`zero`, 会出现`ClassZeroActivity`. 这就是万恶之源,负责弹出霸屏短信的activity,点击它,变红后即代表成功禁用,然后点击下方的`Launch`测试一下是否能正常打开短信.本人亲测禁用这个activity不会影响正常收发短信.

如果你的手机不是安卓原生系统,并且找不到`ClassZeroActivity`,可以尝试搜索`0`,`Flash`一类的关键词,看看有没有相关的activity,自己测试一下.

![6](/pics/6.jpg)

# 你咋知道`ClassZeroActivity`是负责霸屏短信的?
我看的谷歌发的源代码:[点击这个链接查看源码](https://android.googlesource.com/platform/packages/apps/Mms/+/d00f7cd4e92f5c4b86a0827184390a71373f268e/src/com/android/mms/ui/ClassZeroActivity.java)
本人不是安卓开发者,如有错误欢迎指正.






