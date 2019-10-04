# HP-OMEN-15-AX000-Hacintosh
HP 暗影精灵2 Hackintosh support 10.15 Catalina

CPU:Intel i5-6300HQ 
Graphic card: Intel HD 530 
RAM: 16G DDR4 2133Mhz
Wireless card: DW1820A(BCM94350ZAE_2){WLAN:1028:0021 BT:0a5c:6412} CARD NUMER:CN-0VW3T3
原装网卡为英特尔网卡，无法驱动，更换了DW1820A，勉强能用，更新不了系统（重启卡进度条,但是黑果小兵说在BIOS里面屏蔽WIFI和蓝牙之后就能更新了，这个机型的BIOS里面没有相关的选项，所以更新不了），重启不了（卡进度条），睡眠唤醒会freeze,开关WIFI会freeze，蓝牙链接蓝牙耳机会卡顿。
# DW1820A需要屏蔽正面两个针脚，不然开机会很快freeze,网卡我测试了DW1820A :CN-08PKF4（BCM94356ZEPA50DX_2）{WLAN:1028:0023 BT:0a5c:6412}，不管屏蔽还是不屏蔽，都会overload和freeze,不要买这个版本。
handoff和Airdrop可用。
电池正常
声卡正常
核显驱动
亮度音量快捷键可调
插耳机也能自动切换
