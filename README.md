# 电脑上使用ssr的配置教程

## 文章更新提醒
文章于2019-4-20进行了更新

解释了影响酸酸乳速度的因素

按照不同平台的使用重写教程


## Warning
## 注意不要随意分享自己的配置给别人,不要做这种竭泽而渔的事情!!!!!

如果你骚一点,完全可以自己搭建ssr服务,[去vultr租vps就行了(vultr计时收费的方式很适合搭建ssr的)](https://www.vultr.com/?ref=7245982)

至于客户端只要支持ssr协议就行, 不一定要是本教程提到的客户端.

## 0. 步骤梗概
1. 安装ssr客户端
2. 配置客户端(填写账号信息), 可以用ssr链接, 扫二维码, 或手动填写的方式
3. 使用ssr链接或扫二维码的方式配置


## 1. 安装安卓客户端
1. [android客户端下载地址](https://github.com/shadowsocksr-backup/shadowsocksr-android/releases)



## 2. 安装windows客户端
0. [windows客户端下载地址](https://github.com/shadowsocksrr/shadowsocksr-csharp/releases)
1. 将配置*字符串*复制到剪贴板上
1. 只要右键任务栏的ssr小飞机, 点击"剪贴板批量导入ssr://链接"
![差不多是这样的画面](https://upload-images.jianshu.io/upload_images/6813015-7e6918712e607c8f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![ssr配置成功后会填上各行](https://upload-images.jianshu.io/upload_images/6813015-0eda90a6952a0e0e.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 3. IOS客户端(推荐shadowrocket)
0. shadowrocket要到App store美区去下载, 所以要有美区的 appleId, 你可以和朋友借用一下.
1. shadowrock是收费软件(开发者并不是我)
2. 


## 4.日常使用需知
1. 右键任务栏小飞机的图标可选则"系统代理模式"
2. "直接连接"和没有安装ssr是一个效果的,也就是不能翻墙; "pac代理"会根据pac文件自动切换流量的走向的; "全局代理"所有流量都走国外的(看B站这些国内的网站会觉得卡卡的).
3. 注意只有支持sock5的软件才能使用ssr, 即是说浏览器(chrome, firefox)能用ssr, 但是玩游戏就用不了ssr(但是可以配合别的软件实现翻墙打游戏)
4. 简单的理解就是在电脑上浏览器可以直接使用ss代理, 其他的软件用ss代理就需要额外的辅助软件(反正大家只是用来上youtube和pornhub嘛)
3. 不同的运行商网络使用代理的体验(网速)不同
移动 > 联通 > 电信
因为电信的外网出口严重超售(还记得电信的外网加速服务吗?)
5. 不同的地区使用体验也不同()

6. 请不要用代理下载种子(bt), 服务器提供商会封掉代理所用的服务器(不会退款)

## 针对学生用户常见问题排查
1. Q: 为什么用了ssr之后我校园网的登录页面load不出来呀呀呀呀,现在都连不了网啦. 
  - 关闭ssr 或者 pac设置为"直接连接"才能加载出联网的登录页面, 连上校园网后再开启ssr即可
