# MSI-Z490-A-PRO_i7-10700K_RX-6600XT
## 机器配置

|部件|选品名称|参考价格|
|---|---|---|
|CPU|英特尔 i7 10700K|2599|
|主板|微星 Z490-A PRO|1099|
|内存1|海盗船 16GB DDR4 3000 复仇者系列 |628|
|内存2|海盗船 16GB DDR4 3000 复仇者系列 |333.31|
|显卡|蓝宝石 RX 6600XT 白金 OC 8G|3418.88|
|硬盘1|西部数据黑盘 sn750 500G|579|
|硬盘2|威刚 S11 PRO 1TB 固态|580.12|
|机箱|乔思伯 U4 Plus 银色|279|
|电源|长城 GW-600ZN 静音电源（500W）|269|
|CPU散热器|超频三（PCCOOLER）东海逐鹿 GI-D66A 5VRGB|298|
|机箱散热|超频三（PCCOOLER）皓月 12cm 白光|99.49|

## OpenCore 0.7.5
- **机型：** ~~iMac 20,1~~ iMac 19,1
- **系统：** Monterey 12.1 beta

## 正常功能
- 有线网卡
- 无线网卡
- 蓝牙
- 声卡
- 独显
- 睡眠
- USB

## 待完善问题
- [ ] 睡眠唤醒后蓝牙会崩溃
- [x] ~~节能功能开启后主机在熄屏后不主动进入睡眠，手动点击能顺利进行睡眠~~

## 更新时间轴
- **2021.11.13：** 在热心网友的提醒下，将机型由 `iMac 20,1` 调整为 `iMac 19,1` ，考虑到个别应用软件在检测到 20 机型后，会使用到 T2 芯片的解码能力，如优酷客户端无法观看 4K 视频等。
