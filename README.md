
# ASUS A/K501LB Hackintosh Support only 10.12.3 华硕 A/K501LB 黑苹果EFI clover引导文件 只测试了10.12.3。   		
# 感谢insanelymac网站的nguyenlc1993大大，基于他修改的EFI引导适配国行501LB机型。  	
# AirPortAtheros40.kext和VoodooHDA.kext用Kext Utility.app安装。
# 我的501配置如下（换过屏，加了内存条和固态，其他都是原配）： 
# CPU:i5-5200U  显卡：集显HD5500、独显940M（已屏蔽） 		 
# 无线网卡：Atheros AR946X 802.11b/g/n（奇葩卡，10.12上通用硬件ID34就是不能驱动，最终找了几天才找到2208能驱动起来？？？）  
# 有线网卡：瑞昱RTL8168/8111/8112    
# 声卡：ALC233 （用的VoodooHDA驱动，非国行苹果耳机正常、外放和麦都正常，HDMI未测试）  唤醒正常；电源驱动正常；睿频正常；蓝牙只能被搜索，且无法关闭（连接正常）；隔空投送显示（未测试）；FaceTime正常；iMessage正常；iCloud正常；App Store正常；快捷键正常。  
# 此EFI引导只测试了10.12.3，10.12.3以上的版本均出现唤醒有背光，黑屏。查阅了很多资料，注入EDID，修改EDID均无解。感觉基本够用了吧，我小白一个，就折腾到这了，作为体验黑苹果还算完美了，欢迎大佬修复我没测试到的地方。
# 不会编辑凑合看吧。
