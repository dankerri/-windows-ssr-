# 电脑上使用ssr的配置教程
这篇教程分享给与我合租vps的小伙伴
## 文章更新提醒
文章于2018-08-21进行了更新,

移除了关于chrome插件安装的内容

新的客户端有pac模式也有全局模式, 浏览器可以直接使用

## Warning
本教程提供的软件适用于Windows系统,但操作方式在各个系统是一致的
当然前提是:
1. 你拥有一个搭建了ssr-server的服务器
2. 或者拥有连接ssr-server的账号密码
如何购买ssr账号,或者如何搭建ss-server,并不在本文的讨论范围之内

## 0. 步骤梗概
1. 安装ssr客户端
2. 配置客户端


## 1. 安装客户端
1. [下载地址](https://pan.baidu.com/s/19AzL9BB3k_o_RIVDnuWpEA)
提取码： eq2r

2. 压缩包包含以下内容
> - ssr文件夹， ssr的客户端
> - <del>SwitchyOmega.crx， chrome插件文件(不再需要)<del/>
> - <del>GWFList.bak, SwithyOmega.crx的配置文件(不再需要)</del>

![文件](https://upload-images.jianshu.io/upload_images/6813015-354a222ad293cb7c.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## 2. 启动并配置ssr客户端
1. 将配置*字符串*复制到剪贴板上
1. 只要右键任务栏的ssr小飞机, 点击"剪贴板批量导入ssr://链接"
![差不多是这样的画面](https://upload-images.jianshu.io/upload_images/6813015-7e6918712e607c8f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![ssr配置成功后会填上各行](https://upload-images.jianshu.io/upload_images/6813015-0eda90a6952a0e0e.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## 4.日常使用需知
1. 右键任务栏小飞机的图标有pac和全局模式可选
2. pac是会自动切换的, 全局是全局翻的.
3. 注意只有支持sock5的软件才能使用代理, 即是说浏览器(chrome, firefox)能用代理, 但是玩游戏就用不了代理的(但是可以用别的软件转化)
4. 简单的理解就是在电脑上浏览器可以直接使用ss代理, 其他的软件用ss代理就需要很多额外的步骤(反正大家只是用来上youtube和pornhub嘛)
3. 不同的运行商网络使用代理的体验(网速)不同
> 移动 > 联通 > 电信
> 因为电信的外网出口是严重超售的

4. 请不要用代理下载种子(bt), 服务器提供商会封掉代理所用的服务器(不会退款)
