---
typora-root-url: ./caozuo
---

systemctl命令被我们用来启停Linux系统中的软件与服务。

语法如下

systemctl start | stop | status | enable（开机自启动） | disable(关闭开机自启) 服务名

![](./systemctl.png)

演示如上图，可以看出防火墙正在运行

我们使用yum命令安装一个叫做ntp的服务

![](./yum install ntp.png)

我们使用命令systemctl status ntpd来检查这个服务有没有开启

![](./ntpd.png)

很显然这个服务并未被使用

![](./start ntpd.png)

如图，我们成功启用了这个服务