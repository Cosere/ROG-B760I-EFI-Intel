# <font size="7">这是一个基于[OC版本为0.9.4](https://github.com/acidanthera/OpenCorePkg/releases/)生成的EFI配置文件,系统版本Ventura 13.5.1</font>
# （英特尔无线篇，博通网卡点击[这里](https://github.com/Cosere/ROG-B760-EFI-Broadcom)）
#  这是我的使用配置单：
## 主板：
华硕ROG B760I Gaming WI-FI ITX主板
## 主CPU：
英特尔i3-12100（无大小核区分，有大小核的请往下看下面这条）
## 备用CPU：
英特尔i7-13700KF
（已添加[CpuTopologyRebuild.kext](https://github.com/b00t0x/CpuTopologyRebuild)，有大小核的请自行启用，并打开OpenCore的Kernel → Quirks：ProvideCurrentCpuInfo选项）
## 硬盘：
M2接口固态硬盘（该主版不支持SATA协议的M2硬盘）：
&emsp;&emsp;铠侠RC20 2T；
&emsp;&emsp;影驰HOF Extreme 2T；
机械硬盘：
&emsp;&emsp;西部数据2.5寸黑盘WD10SPSX 1T x4
（硬盘选择避开三星那几款具体型号自己查以及据说还有英韧主控的，我也是搜的，能不能用自己尝试）
## 内存条：
宏基掠夺者炫光DDR5 6400CL32 16G x2
（默认XMP就可以，直接拉到6800也可以用，高频请自己手动去超）
## 电源：
ROG LOKI 1000W SFX-L
## 散热：
ROG龙神二代
## 显卡：
蓝宝石590 8G超白金8+6P供电12nm
## 网卡及蓝牙：
有线网卡：板载原装英特尔I1226v
无线网卡及蓝牙：板载原装英特尔AX211
Wi-Fi及蓝牙都正常驱动，隔空随航不可用。
英特尔系列驱动已添加:
>       BlueToolFixup.kext;
>       IntelBTPatcher.kext;
>       IntelBluetoothFirmware.kext;
>       Airportitlwm.kext;
## 请自行注入三码
USB已定制，横向的2.0正常，竖向的两个2.0没定制，因为15个上限。
## 有问题请留言给我
<font color="009788"><font size="8">如果你想要感谢可以请我
喝瓶快乐水！</font></font>
![WechatIMG37](https://github.com/Cosere/ROG-B760I-EFI-Intel/assets/76146442/2f6755ce-dad6-48d4-9436-c7d942f93217)
![WechatIMG38](https://github.com/Cosere/ROG-B760I-EFI-Intel/assets/76146442/638d87a4-7672-4935-ad6e-b0d1f787b5b4)
