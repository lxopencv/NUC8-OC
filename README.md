# NUC8-OC

* NUC8i5BEH/NUC8i7BEH 最新完美OC EFI，补丁、驱动都已更新到最新：

* intel wifi、Bluetooth、雷电3、读卡器均已驱动。

* OC0.9.6-EFI-NUC8-intel-wifi-BT-CardReader-Sonoma：包含自带读卡器、intel wifi和蓝牙驱动，适用于未做任何改动，使用自带读卡器、wifi和蓝牙的机型。

* 默认config.plist 适配4k显示器，OC分辨率配置修改已经变更到UEFI-->Output-->UIScale, 默认该值为0，如果OC分辨率显示不正常可以根据情况，修改为1 或2 尝试，每次修改完最好重置nvram。

* 三码已清，自行更换三码。
  
* --231123: 更新以下测试内容：
  * 免责声明：本人没有以下硬改或转接机型，仅在原版基础上升级oc与kext，测试存在大量风险。安装以下内容前请自行备份原版EFI；测试需要对oc配置方法与调试拥有一定基础，因测试造成的问题本人概不负责。欢迎回报存在问题。
    
  * OC0.9.6-EFI-NUC8-Sonoma-Test:不含自带的读卡器、intel wifi和蓝牙驱动，适用于占用读卡器通道硬改机型

  * OC0.9.6-EFI-NUC8-CardReader-Sonoma-Test：含自带读卡器、无intel wifi和蓝牙驱动，适用于M.2转接白果拆机网卡机型

  * 测试项目一旦有多人回报正常将test文件夹内移动到上层oc


* --231109: 更新NUC8（Macmini8,1）引导以支持系统增量更新。
* --231108: OC更新到0.9.6，支持更新到14.1.1。
