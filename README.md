### 使用硬件
nuc9i9qnx(理论上nuc9全系通用 包括幽灵峡谷 石英峡谷)
无线网卡 板载intel网卡
显卡 6600xt 免驱


### 目前状态

目前来说大体可用，三码请自行添加

#### 已经完善

* [x] 板载的intel无线网卡，速度还不错
* [x] 核心显卡已经驱动但是用的目前的efi中仅作为计算使用，不能驱动输出，如果有需要请修改缓冲帧
* [x] 雷电三载系统信息中能看到，但是手中没有硬件可以测试
* [x] USB接口已经定制，所有usb接口均可以使用
* [x] 声卡驱动正常


#### 未完善
* [] 读卡器没有sd卡测试，但是这个读卡器走的是USB3.2的hub，理论上应该可以使用
* [] 雷电三载系统信息中能看到，但是手中没有硬件可以测试
* [] 有线网卡只有下面的口能用，上面的口插网线会崩溃
* [] 蓝牙我已经按照Monterey的方式去驱动了，但是目前还是打不开

### 其他
暂时够我目前使用，应该还会继续完善。
如果不使用独立显卡，需要修改启动参数将 “agdpmod=pikera” 去掉，并修改核显缓冲帧为 07009B3E 
