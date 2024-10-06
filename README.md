https://twrp.me/oneplus/oneplus6.html


https://eu.dl.twrp.me/enchilada/


https://eu.dl.twrp.me/enchilada/twrp-3.7.0_11-0-enchilada.img

https://eu.dl.twrp.me/enchilada/twrp-installer-3.7.0_11-0-enchilada.zip

https://github.com/topjohnwu/Magisk/releases/tag/v27.0

https://github.com/topjohnwu/Magisk/releases/download/v27.0/Magisk-v27.0.apk



twrp.zip推入手机： `adb push twrp-installer-3.7.0_11-0-enchilada.zip /sdcard/`

Magisk.zip推入手机： `adb push Magisk-v27.0.apk /sdcard/Magisk-v27.0.zip`

   备注 : `Magisk-v27.0.apk` == `Magisk-v27.0.zip`

从adb进入fastboot：`adb reboot bootloader`


临时进入twrp： `fastboot boot twrp-3.7.0_11-0-enchilada.img`

~~在手机的twrp界面刷入 `/sdcard/twrp-installer-3.7.0_11-0-enchilada.zip` 即永久刷入twrp~~

推荐不永久刷入twrp， 每次都临时进入twrp



