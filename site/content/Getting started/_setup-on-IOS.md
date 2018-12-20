---
title: "使用 AppStore 在 IOS 设备上部署软件"
date: 2018-09-10T11:56:40+08:00
draft: false
---
# 下载 App
在App store搜索下载`Shadowrocket`. 但这个应用在国区早就下架了，你需要用国外区的 Apple ID购买
![download_app](https://i.loli.net/2018/06/06/5b17e6fa79852.png)
请购买途中所示的第二个。
# 以订阅链接的方式导入配置
![0_1538386140734_bada378c-33f7-48c2-bb5f-fa492178ca7c-image.png](https://i.loli.net/2018/10/01/5bb1e8df9090d.png) 进入用户中心，图片中红色圈起的链接就是订阅链接。你可以点击`复制`来直接复制他，或者选中这个链接，再点复制
打开 shadowrocket 客户端，点击右上角的加号
![add_config_s1](https://i.loli.net/2018/06/06/5b17e704de8f4.jpg)
点一下上面的类型
![add_config_s2](https://i.loli.net/2018/06/06/5b17e707cc083.jpg)
选择订阅
![add_config_s3](https://i.loli.net/2018/06/06/5b17e705af057.jpg)
如图，粘贴好你的url，然后点右上角的保存
![add_config_s4](https://i.loli.net/2018/06/06/5b17eb9bf3816.jpg)
点击图中圈中的那个按钮打开代理
![turn_on](https://i.loli.net/2018/06/06/5b17e708a6cc5.jpg)
会出现下图所示的情况。点击允许
![trust_app](https://i.loli.net/2018/06/06/5b17e709dc064.jpg)
接下来，会跳转到设置，要求你输入指纹/密码。这是允许这个 app 调用系统的 代理 api 并显示图标。
![end](https://i.loli.net/2018/06/06/5b17e6f8a7bdc.png)
在你正确输入指纹/密码后，会到 app, 就可以切换节点科学上网了
# 使用 SSR 链接导入配置
有的时候，订阅链接会奇怪的不能用，这个时候就可以换成使用 SSR 链接导入配置。

暂时留个坑 以后再填