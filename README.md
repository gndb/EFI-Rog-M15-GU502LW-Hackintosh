ROG 玩家国度 幻15（GU502LW）黑苹果 MacOS Monterey EFI配置文件

### 一、 硬件配置

配置|名称
--|--
CPU|i7-10875H
显卡|Graphics UHD 630
硬盘|Intel 1T SSD+ Samsung 970oveplus 500GB SSD
内存|DDR4 16GB
声卡|板载ALC294
有线网卡| Realtek RTL8168
无线网卡&蓝牙| Intel Wireless AX201

### 二、黑苹果完美成果以及现状

环境|版本
--|--
OpenCore|0.9.5
MacOS Monterey |12.7

已驱动：

* 核显完美(显存已改为2G)
* 声卡完美
* 网卡：有线+无线完美
* 睡眠正常
* 电池管理完美
* 触摸板完美
* CPU、温度传感器正常
* CPU变频正常
* USB 3.0正常
* 声音调节快捷键正常

未驱动：
* 耳机口
* HDMI外接，由于无法驱动独显，而这款HDMI又是独显直通，所以HDMI外接无解

HDMI外接方案：

* 采用USB3.0转HDMI，需要下载驱动，驱动下载地址详见远景帖子：[http://bbs.pcbeta.com/viewthread-1887719-1-1.html](http://bbs.pcbeta.com/viewthread-1887719-1-1.html)

### GitHub

参考：https://github.com/RmondJone/ROG-Zephyrus-M15-Hackintosh-GU502LW
