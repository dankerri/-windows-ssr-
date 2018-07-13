# -windows-ssr-
这篇教程分享给与我合租vps的小伙伴
## 不吐不快
遇到一些事,决定由简书转战github.
事情是这样的教程写完没过几天, 我就收到简书的一则消息,"你的文章已转为仅自己可见."
好好,我懂,文章名字太直白了.
于是我复制粘贴, 又换了名字将文章再发了一遍, 过了两天, 又被封了.
这种事情一次次的发生着,会不会有一天我会习以为常呢?
联想起近日一连串的事件,实在令人感触颇多.
无锡技术学院强迫中国学生为毫无作为的留学生腾空宿舍, 学校发动党员学生做水军,老师人肉反抗的学生,学生微博被关停...
仿佛一个收缩的鸟笼, 一辆向后飞退的坦克.
未来在何处?
我想打开眼睛的人才有可能看见.

## Warning
本教程提供的软件适用于Windows系统,但操作方式在各个系统是一致的
当然前提是:
1. 你拥有一个搭建了ssr-server的服务器
2. 或者拥有连接ssr-server的账号密码
如何购买ssr账号,或者如何搭建ss-server,并不在本文的讨论范围之内
[如果要自己搭建,可以看看这位老哥的文章,很详细](https://www.jianshu.com/p/8812ed9b0966?utm_campaign=maleskine&utm_content=note&utm_medium=seo_notes&utm_source=recommendation)

## 0. 步骤梗概
1. 安装ssr客户端
  - 配置客户端
2. 安装chrome浏览器
  - 在chrome上安装switchyOmega
  - 配置switchyOmega

## 1. 安装客户端
1. [下载地址](https://pan.baidu.com/s/19AzL9BB3k_o_RIVDnuWpEA)
提取码： eq2r

2. 压缩包包含以下内容
> - ssr文件夹， ssr的客户端
> - SwitchyOmega.crx， chrome插件文件
> - GWFList.bak, SwithyOmega.crx的配置文件

![文件](https://upload-images.jianshu.io/upload_images/6813015-354a222ad293cb7c.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## 2. 启动并配置ssr客户端
1. 每次启动ssr客户端都要进入ssr文件夹内,请务必记住ssr文件夹的位置,除非你为它添加了桌面快捷方式
2. 双击ssr4.0，任务栏会出现紫色小飞机图标，双击后出现以下界面，在此处填入配置信息，按确定保存
3. 必填的配置信息有这些:
> - 服务器IP
> - 服务器端口
> - 密码
> - 加密
> - 协议
> - 混淆
> 具体怎么填要询问你们的ssr账号提供商



![ssr配置](https://upload-images.jianshu.io/upload_images/6813015-0eda90a6952a0e0e.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 2.为chrome安装SwitchyOmega
1. 将 SwitchyOmega.crx 像拖拽文件到文件夹一样移到拓展程序界面即可进行安装
2. 若提示不能安装则将浏览器切换至开发者模式
![安装](https://upload-images.jianshu.io/upload_images/6813015-37ff97fbb55568e1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![开发者模式开关](https://upload-images.jianshu.io/upload_images/6813015-14780a8e89bea334.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 3. 配置SwitchyOmega
1. 导出/导入 -> 从备份文件中恢,  导入 .bak 文件即可
2. 最常用的是GWFed 和 自动切换
![导入配置文件.png](https://upload-images.jianshu.io/upload_images/6813015-7d8dd9dfa50c8d64.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![开关](https://upload-images.jianshu.io/upload_images/6813015-39dd5b79797f87ed.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 4.日常使用需知
1. 要科学上网首先就要先打开SSR客户端,SwitchyOmega处于GFWed或自动切换模式
2. SwitchyOmega的选项中
>  - 直接连接，代表不走代理
> - GFWed，代表访问所有的网站都会走ssr代理
>- 自动切换，会根据你的访问列表自动选择走代理或不走代理
>- 所以要是觉得访问网站慢/页面加载不出来,可以尝试更换选项

3. 不同的运行商网络使用代理的体验(网速)不同
> 移动 > 联通 > 电信
> 因为电信的外网出口是严重超售的

4. 请不要用代理下载种子(bt), 服务器提供商会封掉代理所用的服务器(不会退款)

## 5. end
1. 是否需要对原理进行解释?如果需要,请告知我.我会再写一篇关于原理的博客
