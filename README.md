# HP-OMEN-15-AX000-Hacintosh<br>
HP 暗影精灵2 Hackintosh support 10.15 Catalina<br>

CPU:Intel i5-6300HQ <br>
Graphic card: Intel HD 530 <br>
RAM: 16G DDR4 2133Mhz<br>
Wireless card: DW1820A(BCM94350ZAE_2){WLAN:1028:0021 BT:0a5c:6412} CARD NUMER:CN-0VW3T3<br>
原装网卡为英特尔网卡，无法驱动，更换了DW1820A，重启不了（卡进度条），睡眠唤醒会freeze<br>
# DW1820A需要屏蔽5个针脚，不然开机会很快freeze,网卡我测试了DW1820A :CN-08PKF4（BCM94356ZEPA50DX_2）{WLAN:1028:0023 BT:0a5c:6412}，不管屏蔽还是不屏蔽，都会overload和freeze,不要买这个版本。<br>

![avatar](http://7.daliansky.net/DW1820A/DW1820A_Cover_pins.jpg)<br>

handoff和Airdrop可用。<br>
电池正常<br>
声卡正常<br>
核显驱动<br>
亮度音量快捷键可调<br>
插耳机也能自动切换<br>

# 更新可以先进win,然后重启再进安装启动项，就不会卡进度条了<br>

#  如果出现跑完代码（显卡驱动之后）卡进度条的情况可以先进win，然后重启再进macOS就正常，目前也在寻找解决的办法<br>
