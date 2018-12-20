---
title: "在 Windows 电脑上部署软件"
date: 2018-09-10T11:56:41+08:00
draft: false
---
# 部署软件
提供一个客户端下载地址: [下载](https://resources.zqstudio.top/ssr-win.zip) 当然，你也可以去 Github 找 release
下载下来后, 打开. 将这个压缩包的**所有内容**解压到一个文件夹 解压完成后请先不要运行任何软件。
![0_1527484428415_0755a8da-0196-41a5-8cf7-833ff19c323c-image.png](https://i.imgur.com/e1S6rVT.png) 
如果电脑安装了 `.net 4.0` 请使用 `ShadowsocksR-dotnet4.0.exe` 如果电脑只安装了 `.net 2.0`，请使用 `ShadowsocksR-dotnet2.0.exe`
Win10应该默认带了`.net 4.0`, win7好像需要自己去装 `.net 4.0`

如果您不确定自己的电脑有没有安装 `.net 4.0`，那就请直接用 `ShadowsocksR-dotnet2.0.exe` 吧。功能上是没有差异的。
# 关于 SSR 软件的一些说明
## 代理模式
 SSR 软件一共有三个代理模式，他们分别是：直连模式，PAC 模式和全局模式。直连模式就是关闭代理，所有的流量不走 SSR。PAC 模式是按照一个名叫 PAC 的规则文件，决定哪些网站走代理，哪些网站不走代理。而全局模式就是所有网站都走代理。 在运行程序后，您可以在任务栏中右键小飞机，在弹出菜单的最顶部 系统代理模式处随时更改他们。
 ![三种代理模式](https://pic.honoka.club/plugins/imageviewer/site/direct.php?s=b&/Snipaste_2018-10-02_12-14-45.png)

 HonokaCloud 不推荐您使用全局代理模式。
 ## 全局设置
 全局设置可以通过右键 SSR, 在弹出的菜单中选择全局设置来更改
 ![URL=https://pic.honoka.club/c/Snipaste_2018-10-02_14-33-49.png](https://pic.honoka.club/plugins/imageviewer/site/thumb.php?s=c&/Snipaste_2018-10-02_14-33-49.png)
 打开之后，应该是这样的：
 ![detail_global_settings](https://pic.honoka.club/plugins/imageviewer/site/direct.php?s=d&/Snipaste_2018-10-02_14-37-23.png)
 您可以在这里将 SSR 设为开机自动启动以及修改本地 Socks5 端口等信息
# 导入配置
## 单个节点通过SSR链接导入
如果你已经运行了SSR，请先关掉它。进入用户面板。选择你想导入的节点，点击它的小飞机图标
![0_1527484892167_32e147f0-ae48-49a5-8c81-a7848244f3fd-image.png](https://i.imgur.com/vKvGc5k.png) 
弹出了一个窗口，是你的配置链接。这里我的配置是适合`SSR`的，所以全选上面的内容，复制
![0_1527485136718_89a13866-c36a-442d-9fe3-33b1c0b7d9f7-image.png](https://i.imgur.com/tPIlb2J.png)  
运行`SSR`程序，你会在系统托盘看见一个小飞机图标。右键它
![0_1527485275652_b5594180-8c08-47ca-b5fc-b7df718860ae-image.png](https://i.imgur.com/GBt3B6o.png) 
选择`从剪切板导入配置` 稍等一下, 就导入成功了。但这还没完
## 通过订阅的方式导入
![https://pic.honoka.club/plugins/imageviewer/site/direct.php?s=e&/Snipaste_2018-10-02_14-47-20.png](https://pic.honoka.club/plugins/imageviewer/site/direct.php?s=e&/Snipaste_2018-10-02_14-47-20.png)
进入用户中心，图片中红色圈起的链接就是订阅链接。你可以点击`复制`来直接复制他，或者选中这个链接，再点复制
![0_1527485480676_d3d770f6-42ad-42b1-bea7-10ea6957f7a5-image.png](https://i.imgur.com/tWnMQ2n.png) 
右键`小飞机`图标，选择服务器订阅-订阅设置
![0_1527485568423_10a64181-1ddc-43cc-8283-fb3c99438d85-image.png](https://i.imgur.com/rR9Wk7l.png) 
点击 `添加`, 将你刚刚复制的链接粘贴到 `链接` 那里，再点一次 `添加`
![0_1527485704374_3a3e382d-1070-476f-93f8-df8a4e1c199e-image.png](https://i.imgur.com/IeSgaEk.png) 
选中图中所示的那一条，选择 `删除`. 点击ok, 再次右键小飞机，选择服务器订阅，~~更新订阅~~ 点击 更新 SSR 订阅（绕过代理）。不然的话，是无法成功更新的。
~~不过我没成功~~
# 选择服务器
![0_1527487600081_17f7376c-cb59-49f7-ad83-cf60b6d9439f-image.png](https://i.imgur.com/aRoG3ky.png) 
右键小飞机，选择服务器 - 选择正确的组，在 左边/右边 选择你想要的服务器