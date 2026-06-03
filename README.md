基于 老年人Captain 的一键唤醒程序制作
使用本地模型VOSK进行识别 不联网

***下载地址***
推荐使用Microsoft Store直接安装
https://apps.microsoft.com/detail/9mw76kfhnz0c?hl=zh-CN&gl=CN
打开该链接点击在 Microsoft Store 中查看即可下载安装到电脑

***使用说明：***
打开后默认在后台运行 任务栏找到左键打开 选择识别到指定语音唤醒后打开的程序
推荐关闭log 不然每次打开关闭一次都要在你电脑里拉个屎（
开机启动直接在C:\Users\**\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup\下面新建一个快捷方式即可~~ 懒得加开关了


# OneClickXiaoai
一键或者语音快速唤醒PC版小爱同学，全设备兼容

Bilibili: 老年人Captain

原Gitee上的项目，全部迁移至Github

重大更新，支持直接语音唤醒电脑小爱同学，无需点击直接对话。


***旧的使用说明 无视这些：***
注意：必须替换唤醒词为自己的文件，因为一个唤醒词只能激活三台电脑

下载最新版！！！

解压缩到你希望永久存放这个工具的文件夹，而不是桌面或者临时文件夹。

去https://console.picovoice.ai/ 登入，按照视频教程做一个自己的唤醒词，然后下载，解压，重命名为Wakeup.ppn，然后替换文件夹中的Wakeup.ppn！！！

注意：由于picovoice现在限制账号注册，请使用国外注册的谷歌邮箱或者outlook之类的邮箱，并使用VPN登入。

然后在配置文件set.ini中修改key为你的key,Key也可以在https://console.picovoice.ai/ 中找到！！视频忘说这一步了。

最后就可以使用设置工具来启动语音监听功能了。


其中Wakeup.ppn是唤醒词文件，set.ini是设置灵敏度的，xiaoai.exe就是原来那个启动小爱的工具，你也可以继续绑定鼠标宏。

PS：porcupine_params_zh.pv文件是中文模型，如果你希望使用英文唤醒词，请下载官方英文模型然后重命名为porcupine_params_zh.pv替换现有的。https://github.com/Picovoice/porcupine/tree/master/lib/common

