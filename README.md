# i3-12100F-MSI-H610M-BOMBER-RX588-OC0.7.9
===========================================   

MacOS Monterty 12.3+OpenCore 0.7.9   

本机配置：      

☆主板 MSI H610M BOMBER DDR4   

☆CPU intel Core i3-12100F 4 核 8 线程   

☆内存 光威天策 DDR4 3200 8GBx2   

☆显卡 ASUS RX580 8G 2304sp 雪豹   

☆SSD Toshiba TR200 480G+SanDisk Extreme Pro 1TB（WD SN750 1TB）

☆网卡	Intel® I219V Gigabit LAN controller+白果BCM943602CS无线网卡     

===============================================================   

OC版本0.7.9 亲测可驱动MacOS10.15.7-12.3   

已经驱动的部分：   

1.声卡完美驱动（alcid=23）   

2.USB接口正常   

3.音量调节正常   

4.有线无线网卡均正常   

目前无法驱动或有缺陷的部分：   

1.睡眠正常，唤醒后主板上EZ DEBUG LED CPU灯常亮，使用正常   

2.随航无法使用（可连接，黑屏，因无法驱动核显）通用控制正常   

3.CPU睿频开启AppleXcpmForceBoost后正常，关闭选项后可变频但睿频失效（本EFI默认开启）   

自用EFI，感谢Bilibili@国光_大佬的教程   

希望有大佬能帮助我解决1、3两个问题，本人能力所限实在无法修复

ps：发现一个小bug，安装时需将MISC-Security—SecureBootModel设置为Disabled，安装完成后可设置为Default保证系统稳定性（本EFI默认为Disabled）
