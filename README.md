# Android OS products FAQ 

## Android OS ROOT
```diff
- Is your android rooted?
+ Yes, we can rooted android OS for you.
```
## 
## Disable Android add-ons and system apps
```diff
- I mean, can I disable all add-ons in the system and leave only my application and block the
- ability to install other applications except my application? 
+ Yes, we can help you disabled all you want to do. And make the android only work with your app.
```
##
## Install Android ROM
```diff
- Can I install my own Android ROM there? 
+ You can not install you own Android ROM. Android firmware only can work with the right 
+ hardware(include CPU and others). But we can custom your android firmware for you if 
+ you need. And update to you any time.
```
##
## RS232 and UART
```diff
- Does it Support the SPP(Serial Port Protocol)?
+ Yes, Our devices surpport standard serial protocal. It can works with UART TTL mode and RS232 mode.
+ Set the ttyS0 ttyS1 ttyS2 ttyS3 ttyS4  in software is ok
```
## Customer's inquirment
## 
```
- Ok, here is my question. I have RK3588 board which reports this model from kernel device tree: Hugsun RK3588 MINIPC LP4x V1.0 Android Board Now I need kernel changes and Android configuration (device/rockchip/rk3588 changes) so I can make my own firmware. Android 12 SDK from Rockchip I have.
- Hi  . Here's an update. I managed to boot Android on your device using kernel hosted on (I assume) your github: https://github.com/pengyixing/rk-kernel-1.03 If you can share that repository but with git history it would be helpful. Also, from what I see, my wifi/bt configuration is wrong. In device/rockchip/rk3588/wifi_bt.mk I have defined 
+ About the wifi modue. It's ap6275p. You can see in dts file.
+ Do your firmware can read wifi module with kernel?
- Wifi works, I fixed it but bt doesn't.  I didn't debug it yet
+ You wifi config is ok.
- Yes, wifi is ok. I'm not sure why bt is not working  didn't debug it yet 
- Which rockchip sdk you use? Im on rkr8 release 
- Android 12.1
+ I will check for you.
+ Our version is rkr10, Android12.1 . Where do you get the SDK?
- From github, radxa rock5b sbc released it to public
+ Yes, their sbc is open-source.
- I have question. Do you have patchset or does it even exist to support AB partitions? I'm able to build it with ab partitions but uboot doesn't recognize it.
+ I think rock5b sdk have support AB partitions. It should same as SDK from Rockchip.
- Android can be built no problem but uboot isn't configured for ab partition layout, it cant find boot partition (i have uart console so I can confirm it).
+ Do you think Radax have removed the AB partitions config ?
- No, I didn't see anything in git log. They use rk3588evb uboot config and they didn't modify uboot
- Just for your info, i merged rkr10 into my sdk. I don't know if there is newer sdk version where ab works
```
# Ubuntu OS products FAQ

# Debian OS products FAQ

# Others ------
```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
