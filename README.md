https://twrp.me/oneplus/oneplus6.html


https://eu.dl.twrp.me/enchilada/


https://eu.dl.twrp.me/enchilada/twrp-3.7.0_11-0-enchilada.img

https://eu.dl.twrp.me/enchilada/twrp-installer-3.7.0_11-0-enchilada.zip

https://github.com/topjohnwu/Magisk/releases/tag/v27.0

https://github.com/topjohnwu/Magisk/releases/download/v27.0/Magisk-v27.0.apk



#### twrp.zip推入手机

 `adb push twrp-installer-3.7.0_11-0-enchilada.zip /sdcard/`

#### Magisk.zip推入手机

 `adb push Magisk-v27.0.apk /sdcard/Magisk-v27.0.zip`

 备注 : `Magisk-v27.0.apk` == `Magisk-v27.0.zip`

#### 从adb进入fastboot

`adb reboot bootloader`


#### 临时进入twrp

 `fastboot boot twrp-3.7.0_11-0-enchilada.img`

#### ~~永久安装twrp: 在手机的twrp界面刷入twrp.zip~~

 ~~`/sdcard/twrp-installer-3.7.0_11-0-enchilada.zip` 即永久安装twrp~~

**推荐不永久刷入twrp， 每次都临时进入twrp**



#### twrp界面刷入`Magisk.zip`  (root功能由Magisk提供)

twrp界面 :  `Install`  --> 选择 `/sdcard/Magisk-v27.0.zip`  --> 按菜单提示刷入即可

twrp界面点击`Reboot` 以 重启手机进入android ， 已安装Magisk

root功能由Magisk提供


#### 按Magisk提示正常操作即可root

进入android后 点击Magisk应用图片，按提示操作即可

通常需要下载完整Magisk、还可能提示要修改boot.img, 都允许即可