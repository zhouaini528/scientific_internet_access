### 首次搭建

#### 一:需要注册阿里云的帐号，没有注册的可以点击[这边注册](https://account.aliyun.com)

建议使用支付宝登录，因为后面有实名认证，支付宝可以直接认证的。

注册完后建议你去领优惠券，也许还可以给你优惠点[点我领取](https://promotion.aliyun.com/ntms/yunparter/invite.html?userCode=xmsff8ku)

图片有点多，需要等待，不出来多刷新试试。还是不出来只能用这个方法了[点击我](http://47.52.254.110:8096/scientific_internet_access/html/ALIYUN.html)

如图所示：

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/1.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/1.png)


#### 二:登录进去后，左边下拉框点击“云服务器ECS”

如图所示：

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/2.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/2.jpg)


#### 三：进去后点击创建实例

如图所示：

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/3.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/3.png)


#### 四：如何选择配置等等问题

这里有几个重点以及选择的问题。首先预充值至少100元才能购买，你冲个200元如果是个人使用要用很久的，比你买个翻墙的一会儿跑路一会儿不能用划算的多。

1：计费方式怎么选择？包年包月、按量付费、抢占式实例

既然是翻墙被封是常事，包年包月肯定不能选。就剩下按量付费和抢占式实例，其实这两个都可以选择，我偏向选择抢占式实例，毕竟更便宜一点，

2：地域选择？肯定要选择除大陆外的，个人推荐香港。有其他的需求选择其他国家，比如我选择的是新加坡

3：实例配置？ 最低选择是1CPU 0.5G 但是完全够很多人使用了，我这边同时在线6个人都没问题。

4：镜像？首次搭建选择Ubuntu 18.04 64位

5：硬盘？最低选择20G，

6：选择完后点击下一步“网络与安全配置”，没有充值的这步不能执行下去了。

最终配置如下图所示：

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/4.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/4.jpg)


#### 五：网络与安全配置

1：公网带宽？最费钱的选择来了，如何选择？。按使用流量、按固定宽带

人多选择“按固定宽带” 如果纯查看资料、不看视频、不大流量的 选择5M足以。 

一个人就选择“按使用流量” 带宽多大都行，想咋玩就咋玩。

2：其他的选择项默认。

3：点击下一步“系统配置”

最终配置如下图所示：

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/5.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/5.jpg)


#### 五：系统配置

1：这步主要是设置密码，一会登录要使用。其他选项默认。

2：下一步就直接“确定订单”

如下图所示：

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/6.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/6.jpg)


#### 五：创建实例

1：勾选同意《云服务器 ECS 服务条款》

2：点击“创建实例”

3：然后提示创建成功，点击“管理控制台”

如下图所示：

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/7.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/7.png)


创建成功：

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/8.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/8.png)


管理控制台：

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/9.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/9.png)


#### 六：进入系统

1：点击“数据管理DMS”，如果弹出“安全组设置”点击一键设置就行了

2:点击“服务器列表”,我之前有一台所以你们看到是2台

3:点击“系统管理”，会新开一个浏览器的窗口，但是这里有个BUG，它会一直停留在这里页面等待登录，需要你再之前的窗口填写输入输入账户和密码（体验不是很好），账户是root,密码就是刚刚你的设置。

4：回到前一个窗口输入帐号和密码

5：成功进入系统，点击“命令终端”

数据管理DMS：

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/10.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/10.png)


服务器列表：

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/11.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/11.jpg)


系统管理

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/12.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/12.png)


输入帐号和密码

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/13.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/13.png)


进入系统，点击“命令终端”

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/14.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/14.png)


命令终端

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/15.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/15.png)



#### 七：Shadowsocks方式安装梯子

高端的来了，这里有三条命令需要你复制进去（Ctrl+V）

```shell
wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocksR.sh

chmod +x shadowsocksR.sh

./shadowsocksR.sh 2>&1 | tee shadowsocksR.log
```

命令的大神建立者[点击这里](https://github.com/iMeiji/shadowsocks_install/wiki/shadowsocksR-%E4%B8%80%E9%94%AE%E5%AE%89%E8%A3%85)

三行命令一行一行的复制全，如果期间连接服务器断开也没事，按任意键重新连接就行了，之前输入的命令回车后的结果不会消失，接着下一步。

第三条命令后，输入密码后，就一直回车5次，然后等待1-3分钟安全完成。最后出现账户、端口、密码等等。

第一条命令

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/17.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/17.jpg)


第二条命令

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/18.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/18.png)


第三条命令

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/19.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/19.png)


最后结果

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/20.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/20.jpg)

#### 八：最后一步

1:进入ECS服务器列表

2:点击安全组

3:点击配置规则

4:点击快速创建规则

5:添加端口与ip

进入ECS服务器列表

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/21.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/21.png)


点击安全组

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/22.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/22.png)


点击配置规则

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/23.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/23.jpg)


点击快速创建规则

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/24.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/24.jpg)


添加端口与ip

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/25.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/25.png)


#### 九：大功告成

1：下载一个windows的梯子。[下载](https://github.com/shadowsocks/shadowsocks-windows/wiki/Shadowsocks-Windows-%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E)

[安卓梯子](https://github.com/shadowsocks/shadowsocks-android/releases)

[IOS梯子](https://github.com/shadowsocks/shadowsocks-iOS/releases)

2：配置连接帐号与密码

3：启动梯子

4：最后结果

如图所示：

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/26.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/26.png)


如图所示：

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/27.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/27.png)


配置连接帐号与密码

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/28.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/28.png)


启动梯子

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/29.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/29.png)


最后结果

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/99.png](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/99.png)



### 如果被封了，如何快速恢复？

[Aliyun 被封3分钟内解决](./ALIYUN_1.md)


















