# 高速通道 UDPN

高速通道 UDPN 简介

高速通道 （UCloud Dedicated Private Network)，提供各个地域之间的，低延迟、高质量的内网数据传输服务。

## 开通专线

点击控制台左侧，网络-\>高速通道 标签，进入欢迎页。

![image](/images/udpn_welcome.png)

点击上方“开通通道”按钮，在弹窗中，选择线路和带宽。

线路可以选择3种：北京-广州，北京-香港，广州-香港。

![image](/images/udpn_select.png)

## 查看信息

开通专线后，可以看到专线概念信息，包括带宽、费用等。

![image](/images/udpn_information.png)

## 调整带宽

点击控制台上方“调整带宽”按钮，在弹窗中修改带宽。

![image](/images/udpn_resize_bandwidth.png)

## 查看监控

专线概览界面上，可以查看具体的监控信息。

![image](/images/udpn_monitor.png)

## 关闭专线

点击控制台上方的“关闭通道”按钮，在弹窗中确认关闭。

![image](/images/udpn_close.png)

## 注意事项

UDPN高速通道使用隧道封装技术，会产生数据包头的额外开销，且计算进数据包的总长度中。由于隧道的包头字节数固定，
数据报文越大，隧道所占的开销占比越小。
