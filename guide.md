

# 使用指南

高速通道 （UCloud Dedicated Private Network)，提供各个地域之间的，低延迟、高质量的内网数据传输服务。

## 开通通道

在 产品与服务 下的 高速通道UDPN 中，点击 开通新高速通道 按钮。

![image](/images/udpn_welcome.png)

点击上方“开通通道”按钮，在弹窗中，选择线路和带宽。

![image](/images/udpn_select.png)

## 查看信息

开通通道后，可以看到通道信息，包括带宽、费用等。

![image](/images/udpn_information.png)

监控指标说明：

* 网络出口是1分钟采样一次，每分钟直接上报这个采样的值；
* 网络出口峰值是每10s采样一次，每分钟上报6个采样点中，最高的1个值。

## 调整带宽

点击“调整带宽”按钮，在弹窗中修改带宽。调整带宽，费用会按多退少补原则处理，点击 确定 完成调整。

![image](/images/udpn_resize_bandwidth.png)

## 查看监控

专线概览界面上，可以查看具体的监控信息。

![image](/images/udpn_monitor.png)

## 关闭通道

点击“关闭通道”按钮，在弹窗中确认关闭。

![image](/images/udpn_close.png)

## 注意事项

UDPN高速通道使用隧道封装技术，会产生数据包头的额外开销，且计算进数据包的总长度中。由于隧道的包头字节数固定，
数据报文越大，隧道所占的开销占比越小。
