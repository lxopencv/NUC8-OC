# NUC8-OC

* NUC8i5BEH/NUC8i7BEH 最新完美OC EFI，补丁、驱动都已更新到最新：

* intel wifi、Bluetooth、雷电3、读卡器均已驱动。

* OC0.9.7-EFI-NUC8-intel-wifi-BT-CardReader-Sonoma：包含自带读卡器、intel wifi和蓝牙驱动，适用于未做任何改动，使用自带读卡器、wifi和蓝牙的机型。

* 默认config.plist 适配4k显示器，OC分辨率配置修改已经变更到UEFI-->Output-->UIScale, 默认该值为0，如果OC分辨率显示不正常可以根据情况，修改为1 或2 尝试，每次修改完最好重置nvram。

* 三码已清，自行更换三码。

* --231213:  OC更新到0.9.7，支持更新到14.2。
* --231201: 修复3.5mm音频声音不正常问题，支持更新到14.1.2。
* --231109: 更新NUC8（Macmini8,1）引导以支持系统增量更新。
* --231108: OC更新到0.9.6，支持更新到14.1.1。
