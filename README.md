# 电脑上使用ssr的配置教程

## 文章更新提醒
文章于2019-09-31 进行了更新

国庆之后，移动4G用户无法使用代理，软件测试显示可以访问外网，但就是无法访问外国网站。目前还找不到原因和解决方法。
其他网络情况下是没有问题。


## WARNING
### 不要随意分享自己的配置给别人,竭泽而渔的事不可取!!!!! | >  < |!!!!!
不同的网络运营商使用体验不同, 不同区域的使用体验也不同(废话), 对此我表示真的无能为力(两行泪两行泪), 毕竟GFW内部究竟怎么运行的谁也不知道.

其实你可以自己搭建ssr服务,[去vultr租vps就行了(vultr计时收费的方式很适合搭建ssr的)](https://www.vultr.com/?ref=7245982)

至于客户端只要支持ssr协议就行, 不一定要是本教程提到的客户端.

## 0. 通用步骤梗概
1. 安装ssr客户端
2. 配置客户端(填写账号信息), 可以用ssr链接, 扫二维码, 或手动填写的方式
3. 推荐使用ssr链接或扫二维码的方式配置


## 1. 安卓
1. [android客户端下载地址, 请在浏览器中打开,不要在微信中打开](https://github.com/shadowsocksr-backup/shadowsocksr-android/releases)
2. 复制ssr链接
3. 开始安装

step0: 下载apk


![下载链接在asset里](https://github.com/dankerri/-windows-ssr-/blob/master/655819410.jpg?raw=true)


step1

![step1](https://github.com/dankerri/-windows-ssr-/blob/master/1419823127.jpg?raw=true)

step2

![step2](https://github.com/dankerri/-windows-ssr-/blob/master/836383168.jpg?raw=true)

没有显示超时就是成功了

![没有显示超时就是成功了](https://github.com/dankerri/-windows-ssr-/blob/master/865406701.jpg?raw=true)


## 2. windows
0. [windows客户端下载地址](https://github.com/shadowsocksrr/shadowsocksr-csharp/releases)
1. 解压后运行4.0的快捷方式
1. 将配置*字符串*复制到剪贴板上
1. 只要右键任务栏(屏幕的右下方)的ssr小飞机, 点击"剪贴板批量导入ssr://链接"


![差不多是这样的画面](https://upload-images.jianshu.io/upload_images/6813015-7e6918712e607c8f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![ssr配置成功后会填上各行](https://upload-images.jianshu.io/upload_images/6813015-0eda90a6952a0e0e.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 3. IOS(推荐shadowrocket)
0. shadowrocket要到App store的美区去下载, 所以要有美区的 appleID, 你可以和朋友借用一下.
1. shadowrock是收费软件(开发者并不是我)
2. 将二维码的图片保留在手机里
3. 开始安装

step1

![step1](https://github.com/dankerri/-windows-ssr-/blob/master/1521190801.jpg?raw=true)

step2

![step2](https://github.com/dankerri/-windows-ssr-/blob/master/2013973155.jpg?raw=true)


### 4. mac
0. [不熟悉mac所以只贴教程](https://ssr.tools/164)




## 4.日常使用需知
1. 右键任务栏小飞机的图标切换"系统代理模式"
2. "直接连接"和没有安装ssr是一个效果的,也就是不能翻墙; "pac代理"会根据pac文件自动切换流量的走向的; "全局代理"所有流量都走国外的(看B站这些国内的网站会觉得卡卡的).
3. 在电脑上浏览器可以直接使用ss代理, 其他的软件用ss代理就需要额外的辅助软件(反正大家只是用来上youtube和pornhub嘛), 在手机上所有应用都能使用ss代理.
5. 不同的地区使用体验也不同(不同区域的ISP有自己的封禁策略)
6. 请不要用代理下载种子(bt), 服务器提供商会封掉代理所用的服务器(不会退款)

## 针对学生用户常见问题排查
1. Q: 为什么用了ssr之后我校园网的登录页面load不出来呀呀呀呀,现在都连不了网啦. 
  - 关闭ssr 或者 pac设置为"直接连接"才能加载出联网的登录页面, 连上校园网后再开启ssr即可
  
2. Q：就算关闭ssr，微信可以使用, 浏览器却没法上网了
  - 浏览器的代理服务器设置会被修改, 手动改回来就行了
  [按照这个步骤操作](https://blog.csdn.net/wingter92/article/details/78047527)
  
