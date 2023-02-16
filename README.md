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
+ Set the ttyS0 ttyS1 ttyS2 ttyS3 ttyS4  in software is ok.

##
Question, if i want to have player with 4G/5G how can we do that?
+That RK3588 Media player can not support ,but we have another product for you.
-i guess we could use a USB stick?
+Yes, can use USB stick. I have gave you another specification for new RK3588, the bigger one,it can add module inside.
-This is a case for another customer.. So it would be great if i could use same players.

##Firmware
-i see you have a small deviation from our install description in the image.
+Can you send me images?
-We add a refresh to the chrome browser every 3 hours.
-This was in your factory image added to sudo crontab -e
-But according to the install manual, this should be in crontab -e (not sudo cause the Chrome browser is running as the current user)
-Here is from the install manual:Then add cronjob to run the script. crontab -e Add line:  0 /3    chromium-refresh
+For refresh chrome you can check in terminal “sudo crontab -l”
-We are not sure if this will have any difference, but when we set up RPI4 devices, this is an important detail.
-One more thing, could you please add "terminal" to desktop favorites menu.
+execute the refresh script by manual and the chrome will refresh normally
+We have checked the firmware is good now---xxxxx_rk3588_mini_box_debian_gnome_20220926_v1.1---is sending now
-Great, now it is correct now.

```
##
## Support HDMI and USB in
```diff
- What about the HDMI and USB in?
+ It support USB Host 3.0 and USB Host 2.0 .It is android system, you need the HDMI input?
- So it does not have HDMI input?
+ Yes, only has output now. And we can also do the input, but only can choose on from in and out
- But the input support with touch?
+ It is support, can achieve it by the USB
```
##
## Support HDMI OUTPUT
```diff
-  And the HDMI loop out?
+ Yes it supports HDMI output.
```
##
## Kernel device tree
```diff
- Ok, here is my question. I have RK3588 board which reports this model from kernel device tree: Hugsun RK3588 MINIPC LP4x V1.0 Android Board Now I need kernel changes and Android configuration (device/rockchip/rk3588 changes) so I can make my own firmware. Android 12 SDK from Rockchip I have.
```
# Instal google home or Alexa APP
```diff
- If I install the Alexa APP or google home, and chat with your device, will alexa respond? Just like with a smartphone.
+ No problem, You can download via google store
```
##
## Kernel device
```diff
- Ok, here is my question. I have RK3588 board which reports this model from kernel device tree: Hugsun RK3588 MINIPC LP4x V1.0 Android Board Now I need kernel changes and Android configuration (device/rockchip/rk3588 changes) so I can make my own firmware. Android 12 SDK from Rockchip I have.
```
##
## Customer's inquirment
```diff
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
-?Android can be built no problem but uboot isn't configured for ab partition layout, it cant find boot partition (i have uart console so I can confirm it).
+ Do you think Radax have removed the AB partitions config ?
- No, I didn't see anything in git log. They use rk3588evb uboot config and they didn't modify uboot
- Just for your info, i merged rkr10 into my sdk. I don't know if there is newer sdk version where ab works
```
##
## Support HDMI and USB in
```diff
- What about the HDMI and USB in?
+ It support USB Host 3.0 and USB Host 2.0 .It is android system, you need the HDMI input?
- So it does not have HDMI input?
+ Yes, only has output now. And we can also do the input, but only can choose on from in and out
- But the input support with touch?
+ It is support, can achieve it by the USB
```
##
## Support HDMI OUTPUT
```diff
-  And the HDMI loop out?
+ Yes it supports HDMI output.
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

