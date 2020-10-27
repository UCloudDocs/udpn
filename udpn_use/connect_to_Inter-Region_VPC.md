#  跨地域内网打通

VPC打通注意事项详见 [VPC规划](https://docs.ucloud.cn/vpc/configurationguide/vpcguide)-VPC联通规则。

## 方法一：UDPN页面进行跨地域内网打通
### 1、购买UDPN线路

进入到[控制台UDPN页面](https://console.ucloud.cn/udpn/udpn)，点击**开启高速通道**，选择购买需要打通的可用区的线路。

假如我们需要广州的VPC1联通在北京二的VPC2，购买广州-北京二（或者北京二-广州都是一样的）的线路即可。
![](/images/create_udpn.png)

如果已经购买了需要打通地域的UDPN线路，则直接进行下一步。

### 2、进行VPC打通
UDPN网络互通页面，广州选中VPC1，点击**VPC联通管理**，在弹出的页面中选中需要联通的VPC2，点击确认，即可完成跨地域内网联通。
![](/images/create_connection.png)


> 提示：点击UDPN-网络互通页面中***切换*** 后刷新，地域信息展示会切换视角。



联通后可以在UDPN概览页面分别查看线路两地的出口带宽。
![](/images/udpn_watch.png)

在VPC页面也能查看到其联通情况。
![](/images/udpn_watch2.png)

## 方法二：VPC页面进行跨地域内网打通
