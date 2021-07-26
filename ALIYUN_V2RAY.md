### 首次搭建

图片有点多，需要等待，不出来多刷新试试。还是不出来只能用这个方法了[点击我](http://47.52.254.110:8096/scientific_internet_access/html/ALIYUN_V2RAY.html)

#### 一:需要注册阿里云的帐号，没有注册的可以点击[这边注册](https://account.aliyun.com)

建议使用支付宝登录，因为后面有实名认证，支付宝可以直接认证的。

注册完后建议你去领优惠券，也许还可以给你优惠点[点我领取](https://promotion.aliyun.com/ntms/yunparter/invite.html?userCode=xmsff8ku)

如图所示：

![https://github.com/zhouaini528/scientific_internet_access/blob/master/img/aliyun/1.jpg](https://github.com/zhouaini528/scientific_internet_access/blob/master/img/aliyun/1.jpg)


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

2：地域选择？肯定要选择除大陆外的，北方的可以选择日本，南方可以选择香港，离你最近选择。有其他的需求选择其他国家，比如我选择的是新加坡（流量要比香港便宜一半）

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



#### 七：V2Ray方式安装梯子（推荐用这种方式，被封几率小）

高端的来了，这里只有一条命令需要你复制进去（Ctrl+V）

```shell
bash <(curl -s -L https://git.io/v2ray.sh)
```

第一步选择 1  ，然后就一直回车下去。

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/1.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/1.jpg)

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/2.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/2.jpg)

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/3.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/3.jpg)

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/4.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/4.jpg)

最后安装结果。一定要复制出最后生成的所有信息

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/5.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/5.jpg)


#### 八：最后一步，配置端口，打开防火墙

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

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/6.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/6.jpg)


#### 九：大功告成，下载梯子

梯子的客户端下载
https://tlanyan.me/v2ray-clients-download/

我windows下载的是V2RayN。其实系统的按照对应的来

如图所示：

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/7.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/7.jpg)

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/8.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/8.jpg)

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/9.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/9.jpg)

最后，选择你刚刚添加的服务器，并启动http代理，推荐用PAC模式

![http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/10.jpg](http://47.52.254.110:8096/scientific_internet_access/img/aliyun/v2ary/10.jpg)


如果还有不懂的可以看看这个[点击这里](https://github.com/233boy/v2ray/wiki/V2Ray%E6%90%AD%E5%BB%BA%E8%AF%A6%E7%BB%86%E5%9B%BE%E6%96%87%E6%95%99%E7%A8%8B)

### 如果被封了，如何快速恢复？

[Aliyun 被封3分钟内解决](./ALIYUN_1.md)
