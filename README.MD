# Magisk
Static binaries included:
* Busybox: http://forum.xda-developers.com/android/software-hacking/tool-busybox-flashable-archs-t3348543


* [2016.10.4] Magisk v7: http://forum.xda-developers.com/apps/magisk/official-magisk-v7-universal-systemless-t3473445

Magisk Is A Magic Mask to Alter System Systemless-ly

Hello, welcome to the official Magisk Release / Announcement thread!
The biggest limitation of systemless mods is that you can only bind mount things to existing items inside the system, and the bind mounting doesn't happen early enough to make an effect. This limited the usage of systemless mods in general. Systemless mods used to be complicated and not easy to maintain, and also not always possible (new libs / bins / framework or any other files / folders are required to be added), and this is why not all mods are systemless.

Magisk aims to overcome these difficulties and create a universal interface to modify your system - without actually modifying the system!
Developers can easily create a Magisk Module, and users will only need to install them to enjoy your marvelous mods - systemless-ly of course!!

!! This mod requires, and only do boot image modification !!

To developers: Feel free to open a new thread with additional support for your own device!

Features
Magisk Manager: 
Install / Upgrade Magisk in-app. Manage, Upgrade, Download, Install Magisk Modules within a few taps.
Magic Mount: 
This feature will not only allow you to replace existing file and directories, but also support adding new files and directories into system!
What this means is that all existing mods should all be possible to work systemless-ly!
Multiple Entry Points: 
Magisk provides several entry points to developers to run scripts at different boot times, reliably blocking the boot process to continue before your scripts are done. This allows experienced developer to fine tune the Magisk Module's behaviour.
"post-fs" a.k.a "Cache" Mode: 
This mode runs before system props are loaded (and before /data is mounted), which brings systemless mods to the next level
Systemless host support enabled by default, you can use Adblock apps without additional configuration
Built-in busybox which extends support back to Lollipop (5.0).
Magisk will remove verity / forceencrypt (both are configurable through .magisk file), and patches sepolicy
Possibilities
All mods on XDA can be systemless, including root and Xposed
Custom roms without flashing to system (good for stock modded roms)
Eventually might lead to universal Multirom support for all devices (Concept only, haven't started to work on it yet)
Installation Instructions
(NOTE: I don't feel comfortable to redistribute SuperSU unless I have explicit permission, so for now, if you want to use SuperSU with Magisk, you are required to have systemless SuperSU installed before flashing Magisk. Magisk will detect SuperSU installation and automatically convert systemless SuperSU into a Magisk Module, using the files that are already installed to your boot image. System installed SuperSU is obviously not supported, since it is not systemless. Actually, it is a trivial task to add official Magisk support to a SuperSU zip package, however the decision is not in my hands.)

If you're rooted with Official Systemless SuperSU, or using Magisk v3+ with Magisk version of phh's superuser
Install the latest Magisk Manager
Install/upgrade Magisk as prompted in the application
Reboot and you're done!!
