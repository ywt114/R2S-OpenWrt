## R2S 基于原生OpenWRT 的固件(AS IS, NO WARRANTY!!!)

### 注意事项：
0.OC至1.608GHz（未提升电压，原则上不会增加大量额外发热）

1.登陆IP：192.168.1.1 密码：无

2.OP内置升级可用

3.遇到上不了网的，请自行排查自己的ipv6联通情况。（推荐关闭ipv6

4.刷写或升级后遇到任何问题，可以尝试ssh进路由器，输入fuck，回车后等待重启，或可解决

5.从2020.8.1开始重新交换 LAN WAN，解决千兆环境下IDM下载掉速的问题，用户注意！！！！！（当前靠外的是LAN，靠中心的是WAN）

6.sys灯引导时闪烁，启动后常亮，是上游的设定，有疑问请联系OP官方社区

### 版本信息：
其他模块版本：SNAPSHOT（当日最新）

LUCI版本：19.07（当日最新）

### 特性及功能：
1.O2编译

2.内置三款主题

3.插件包含：VSSR，PassWall，OpenClash，AdguardHome，BearDropper，微信推送，网易云解锁，SQM，SmartDNS，ChinaDNS，网络唤醒，DDNS，迅雷快鸟，UPNP，FullCone(防火墙中开启)，流量分载(防火墙中开启)，SFE流量分载(也就是SFE加速，防火墙中开启，且默认开启)，BBR（默认开启），irq优化，OLED屏幕支持，京东签到，Zerotier，FRPC，FRPS，无线打印，流量监控

4.核心频率1.608GHz
