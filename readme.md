HTC DNA:

* Follow HTCDev to unlook phone
* Root Phone
* Enter fastboot
* Replace recovery with TeamWin
	* `fastboot flash recovery twrp.img`
* Install new ROM
	* `fastboot flash boot boot.img` (from zip archive of install)
* Enter Recovery
* Copy over and apply: 
    * Apply update.zip of the new ROM
    * Apply HTC-DNA_20151117-UPDATE-SuperSU-v2.46.zip