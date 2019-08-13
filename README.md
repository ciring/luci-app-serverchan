# 说明
- 源码来自https://github.com/KFERMercer/OpenWrt/tree/master/package/kferm/luci-app-serverchan 
- 修正了K3温度不能获取的错误
- 增加了辣鸡流量信息统计
- 用于 K3 OpenWRT/LEDE 路由器上进行 Server酱 微信推送的插件
- 基于 serverchan 提供的接口发送信息，Server酱说明：http://sc.ftqq.com/1.version
- 已经自带 luci

#### 主要功能
- 路由 ip 变动推送
- 设备别名
- 设备上下线推送
- CPU 负载、温度监视
- 定时推送设备运行状态
- MAC 白名单、黑名单、仅检测某接口设备
- 免打扰时间
- 流量信息

#### 预览截图

![image](https://www.skeimg.com/u/20190813/17281668.png)

![image](https://www.skeimg.com/u/20190813/17281548.png)


#### 已知BUG & 下一步计划
- 网络流量的bug很多
- 无法汇总到一个框里
- 网口信息可能不对，具体根据自己情况改root/usr/bin/serverchan第444行左右代码
- 为了方便，整个部分做在了在线设备的代码块里，可能导致不知名的bug

#### 暂时没有精力修复，将就着用吧

