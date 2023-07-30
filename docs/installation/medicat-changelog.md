---
title: Changelog
layout: default
parent: Installation
---

<details markdown="block">
<summary>Version 21.12</summary>

Changelog for v21.12:
---

### Added:
* AOMEI Backupper, DiskGenius, EasyUEFI, Macrium Reflect, MiniTool ShadowMaker, and Symantec Ghost boot disks have been have been restored as bootable ISOs. (.wim files, more accurately.)
* Windows 11 Recovery disc was added to the Windows Recovery menu, and I disabled the TPM 2.0 and CPU checks myself.
* BIOS Beep Codes Verifier 1.0.3.1036 to PortableApps menu.
* UEFITool v0.28.0 to PortableApps menu.
* UEFI BIOS Updater 1.69.17.2 (Converted from .bat to .exe by me) to PortableApps menu.
* Dell 64BIT BIOS Flash Utility v3.3.1, A03 (Icon added by me) to PortableApps menu.
* ASUS WinFlash v3.2.10, (PortableApps menu)
* Prime95 v30.8, build 3, (PortableApps menu)
* MediaCreationTool for Windows 11, (PortableApps menu)
* MediaCreationTool [AIO], (PortableApps menu) a batch file tool that I converted to .EXE which can download Windows ISOs for you. Also includes a .bat file to patch Windows 11 ISOs against TPM and CPU checks.
* Windows 11 Fixer, (PortableApps menu) to fix Windows 11 annoyances.
* Windows Install Assistant, (PortableApps menu) to check if your Windows meets the requirements to install Windows 11.
* Partition Bad Disk, (PortableApps menu)
* LICENSE.txt to the root of the USB.
* "Administrator" user folder shortcut on the Mini Windows 10 desktop.
* Added "The Official Website" URL shortcut to the Mini Windows 10 desktop, as well as in the Google Chrome Bookmarks bar.


### Removed: 
* My personal SSID and Wi-Fi password have been removed from Wifi.bat (Oops!)
* Problematic apps that would throw up errors or prompt you for a license have been removed.
* OnlyOFFICE Portable, to save drive space.
* Versioning numbers have been removed from the menus for a cleaner look. You can find the version information by checking the Submenu with F6.
* NIUBI Partition Editor, to save drive space.
* O&O BlueCon, to save drive space.
* The 32-bit menu of Lockpick has been removed, as it was a useless waste of space.

### Updated Apps:
* Many PortableApps have been updated.
* Ventoy to v1.0.63
* 7-zip to v21.06
* Tor Browser updated to v11.0.2, and is now set to auto-connect to the Tor network upon opening it. 
* Snappy Driver Installer Origin updated to vR739
* PCUnlocker updated to v5.6 in Lockpick.

### Updated Images:
* EaseUs Partition Master to v16.5
* Parted Magic to v2021.11.17
* MiniTool Partition Wizard to v12.6
* ShredOS to v2020.05.017, build v0.32.003_20211111
* AOMEI Backupper to v6.8.0
* AOMEI Partition Assistant to v9.5.0
* Jayro's Lockpick has been upgraded to a Windows 11-based WinPE.
* Boot-Repair-Disk to v2021-12-16
* EasyUEFI to v4.8
* Rescatux v0.74
* SystemRescue to v8.07
* PassMark MemTest86 to v9.3.1000 [Intel/AMD]
* PassMark MemTest86 to v9.3.1000 [ARM64/AARCH64]
* EaseUS Todo Backup to v13.5.0, build 20211123
* Macrium Reflect to v8.0.6353
* HDAT2 to v7.4
* MiniTool Power Data Recovery to v10.2
* Active@ Data Studio to v18.0.0
* ShredOS to v2020.05.016, Build 0.32_20211029

### Menu Changes:
* I have completely pain-stakingly rewritten ventoy.json, so that anyone can drop in a new updated .IMG, .ISO, .VHD, or .EFI file and rename it in the folder. This means you no longer have to edit ventoy.json when updating your bootable files.
* As a result of the re-write above, the folder structure has also changed to not only take advantage of the new menu, but also in aiding users with tooltips under the menu, giving descriptions of the tools, and telling users wether the tool supports BIOS, UEFI, or both.
* Backup_and_Restore has been renamed to Backup_and_Recovery.
* Boot_an_Operating_System has been renamed Live_Operating_Systems.
* A few icons have been adjusted, and a new icon for UEFI files has been made.
* Version info has been updated.
* New Wallpaper
* Added a holiday hat to the mascot.

### Other Misc. Changes:
* The Driverpacks in USB:\PortableApps\SnappyDriverInstaller\Drivers\ have been repacked with the latest 64-bit Windows 10 drivers (and all others removed.)
* The latest storage drivers have been integrated into Mini Windows 10's .wim file.
* A new desktop icon is on the Mini Windows 10 desktop, taking the user to the new MediCat website. (medicatusb.xyz)

### Fixes:
* The Malwarebytes Bootable WinPE now boots up Malwarebytes v2.2.1.1043, and completes virus scans without crashing. (Please see the _READ_ME!_.txt file at USB:\Programs\MalwarebytesPortable\ for more information.) Thanks @Gremlin220366#4797 for the new Malwarebytes Portable build!
* Fixed the Wallpaper setter so it sets the wallpaper properly in Mini Windows 10. It sometimes wouldn't set in VMware testing, and has been fixed within pecmd.ini.
* Also fixed Rainmeter not launching in certain instances.
* Further improvements to overall system stability and other minor adjustments have been made to enhance the user experience.

Project Contributors:
---

* MON5TERMATT contributed countless hours of his free time towards the installer of this project, the new website, server boosting, server moderation, seeding MediCat torrents, creating and maintaining the server bots, and more. He is a one man army, and is an invaluable asset to the MediCat dev team!
* Daan Breur (Daan Breur#6262) on the MediCat Discord server contributed PowerShell code for the MediCat USB Installer during the Beta program. Thanks Daan!
* AAA3A has also dedicated numerous hours of his time to the project, contributing cog modifications to the server bots, bringing forward updated versions of Lockpick, file hashing algorithms, updating wallpaper scripts, testing portable applications, and many other large and small contributions. His dedication to the project is immeasurable, and I'm glad he's on the MediCat dev team!
* Gremlin220366#4797 has been testing apps for us, helping us pin down troublesome applications. We really appreciate his efforts! He also supplied us with the new v2.2.1.1043 build of Malwarebytes Portable, to fix the crashes during a scan.
* COFF33NINJA#1282 for suggesting the MediaCreationTool (MCT) that's been added.
* A special thanks to the beta testers of the new MediCat installer. Thank you all for your time and dedication!
</details>

<details markdown="block">
<summary>Version 21.06</summary>

Changelog for v21.06:
---

### Added:
* Discord Portable has been reinstated and works again. It's a little slow to startup and update itself, etc... but it does work.
* DeepL Translator app in the PortableApps menu, for more fluent and smarter translations.
* WBG Windows Password Reset was added to Jayro's Lockpick by @AAA3A
* @AAA3A created a Startup.bat script that loads anything placed into the Y:\System\Startup\ folder once the desktop loads in. This can be useful for opening a custem application you like, or a notepad document, for example.
* @AAA3A and I have added a custom Wallpaper Changer script to Mini Windows 10. Place your custom background.png into the Y:\System\ directory (Y:\System\background.png) and your custom wallpaper will be set upon the desktop loading in. If you do not have a wallpaper located at Y:\System\background.png, the defaut wallpaper from X:\Windows\Web\Wallpaper\Windows\img0.jpg will be provided for you.
* A Wi-Fi connection generation script was made by @AAA3A, and added to the build. What you do is edit Y:\System\Startup\Wifi.bat with your network's SSID and Password, and switch the "set generation" flag to a capital 'Y'. Run the Wifi.bat, and it will generate you a Wifi.xml file. Then edit the "set generation" flag back to a capital 'N' and save it. Now it will connect to your Wi-Fi network automatically every time you boot up Mini Windows 10.
* MON5TERMATT#9999 on the MediCat USB Official Discord server compiled AAA3A's batch file to an EXE that launches Tor Browser from the PortableApps Menu.
* OnlyOffice Desktop Editor Portable has been added to the PortableApps Menu.
* Many, many, MANY applications have been added to the Start Menu. Be sure to check out the entire thing, it's LOADED with applications now!
* Exported previous MediCat USB wallpapers to the Themes folders, so you can now choose any of the previous MediCat USB wallpapers.
* New icon theme for the PortableApps menu, made by Discord user ijahangard#8048.


### Removed: 
* Extra copy of ShredOS I forgot to remove in the last version.

### Updated Apps:
* Many PortableApps have been updated.
* Ventoy to v1.0.46
* Jayro's Lockpick (the WinPE) was rebuilt by me using WinBuilder.
* Jayro's Lockpick (the application) was updated by @AAA3A.
* Mini Windows 10 was rebuilt from the ground up using Windows 10 Pro v2004 in WinBuilder. This brings many improvements, like better Wi-Fi drivers and trackpad support for HP laptops.
* Malwarebytes Bootable (the WinPE) was rebuilt using WinBuilder.
* Added a craptop of Apps in the Mini Windows 10 Start Menu. Lots to choose from now.


### Updated Images:
~ Rescuezilla to v2.2 [UEFI]
~ Macrium Reflect to v8.0.5994 [UEFI]
~ Mini Windows 10
~ Jayro's Lockpick
~ Malwarebytes Bootable

### Menu Changes:
* Version info has been updated.
* New Wallpaper
* Better spacing adjustments for the F-key buttons at the bottom, since [F7] was added.



### Fixed:
* Better trackpad support in Mini Windows 10, Malwarebytes Bootable, and Jayro's Lockpick.
* Rebuilt Malwarebytes Bootable - When you update the Virus Definitions, make sure you exit the app in the task tray, and re-open it so the new definitions take hold. Otherwise you may BSOD. And on that note, when running a custom scan, make sure you uncheck all 4 boxes on the left side to mitigate your chances of getting a BSOD.
* Further improvements to overall system stability and other minor adjustments have been made to enhance the user experience.
</details>

<details markdown="block">
<summary>Version 21.05</summary>

Changelog for v21.05:
---

### Added:
* The [F6] button's extra GRUB menu has been completely overhauled by GBATemp user @AAA3A, and has collaborated with me to bring you a robust information menu where you can see the changelog, the list of bootable tools, and many other nice additions to the Main Menu.
* The [F7] button switches between the graphics mode and text mode on-the-fly without having to reboot the computer.

### Removed: 
* Portable Discord client - It stopped working with the recent updates, and I'm still trying to figure it out. It will hopefully come back someday... but for now, just use Discord in the Chrome browser.

### Updated Apps:
* Many PortableApps have been updated.
* Ventoy to v1.0.45
* Jayro's Lockpick was updated by @AAA3A

### Updated Images:
* Acronis True Image to v2021 Build 39216 [UEFI]
* EaseUS Partition Master to v15.8 [UEFI]
* AOMEI Backupper to v6.4 [UEFI]
* AOMEI Partition Assistant v9.2.1 [UEFI]
* SystemRescue to v8.03 [UEFI]
* Parted Magic to v2021.05.12 [UEFI]
* EasyUEFI to v4.6.2 [UEFI]
* Acronis Cyber Backup to v12.5 Build 16428 [UEFI]
* HDAT2 to v7.2 AIO [BIOS]
* ShredOS to v2020.05 [UEFI]

### Menu Changes:
* Version info has been updated.
* New wallpaper.
* Moved the MediCat USB versioning info to the top of the menu so it's easier to read, regardless what the wallpaper has going on or the colors used.
* Moved the [MEMDISK] and WIMBOOT tags to the bottom of the main menu, so they're easily visible when they're active.

### Fixed:
* Rebuilt Malwarebytes Bootable - When running a custom scan, uncheck all 4 boxes and you won't get the BSOD.
* Further improvements to overall system stability and other minor adjustments have been made to enhance the user experience.
</details>

<details markdown="block">
<summary>Version 21.03</summary>

Changelog for v21.03:
---

### Added:
* PassMark Memtest86 Pro v9.0 for [ARM64/AARCH64] [UEFI]: Since Ventoy added ARM64/AARCH64 support, I figured it couldn't hurt to add this version for people with ARM64 hardware. Though I don't have any ARM64 computers myself, so it's completely untested by me. Any feedback of it working or not is greatly appreciated.

### Removed: 
* Replaced MiniTool Partition Wizard with AOMEI Partition Assistant, as MiniTool wouldn't launch under WinPE. Please Note: When you launch AOMEI Partition Assistant, it changes the screen resolution to 1024x768, and I'm not sure how to stop it from doing that. It's just a harmless side effect we'll have to live with for now.

### Apps:
* Many PortableApps have been updated.
* Ventoy to v1.0.38
* Wabbitemu's TI-83 Plus OS has been upgraded from v1.13 to v1.19 of the OS.

### Updated Images:
* Acronis True Image to v2021 Build 39184 [UEFI] (Huge bug-fix version.)
* EaseUS Todo Backup to v 13.5.0 [UEFI]
* AOMEI Backupper to v6.4 [UEFI]
* NIUBI Partition Editor to v7.4.1 [UEFI]
* Symantec Ghost x64 to v12.0.0.11331 [UEFI]
* SystemRescue to v8.01 [UEFI]
* O&O BlueCon to v18.0.8088 [UEFI]
* Parted Magic to v2021.02.28 [UEFI]
* EasyUEFI to v4.5.1 [UEFI]
* PassMark Memtest86 Pro to v9.0 stable [UEFI]
* BootIt Bare Metal to v1.70 [BIOS]

### Menu Changes:
* Version info has been updated.
* New wallpaper.

### Fixed:
* Edited Lang.ini in the boot.wim of "MiniTool Power Data Recovery v9.2" from Spanish (Language=58) to English (Language=31), so it now boots in English.
* Returned Malwarebytes Bootable to the 2018 WinPE, as scans were unable to be finished by the 2016 WinPE in the v12.01 release.
* Set the "BootIt Bare Metal v1.70" ISO  under the "auto_memdisk" section of ventoy.json, so it just boots properly with the press of the ENTER button.
* Further improvements to overall system stability and other minor adjustments have been made to enhance the user experience.
</details>

<details markdown="block">
<summary>Version 21.01</summary>

Changelog for v21.01:
---

### Added:
* If MediCat VHD (New project!) is added to a MediCat USB drive, it will automatically generate a folder for it on the Main Menu. From within that VHD folder, you can launch MediCat VHD, and it runs a full Windows 10 installation on your computer. It is far less limiting than Mini Windows 10. MediCat VHD must be downloaded separately, and is 20GB in size. So a 64GB MediCat USB flash drive is the minimum requirement to have them together. MediCat VHD will of course work alone on it's own 32GB USB drive.
* Simple Vhd Manager v1.4 added to the PortableApps menu.
* Mouse cursors no longer look ugly in Mini Windows 10, I added the Cursors folder to C:\Windows to resolve this.
* Memtest86+ v5.31 Beta has been added as a BIOS-bootable Memory tester. This was added because Memtest86 v9.0 is UEFI-only, so now there's a memory tester for each boot mode. Memtest86+ v5.31 Beta has been added to the auto-MEMDISK list, and is transparent to the user. It also adds a nice Shutdown/Restart/Exit menu when exiting the app.
* WinNc v9.7.0.0 added to PortableApps menu. It's a modern, feature-rich tabbed file explorer with a nice Windows 10 interface.
* RS RAID Retrieve v1.3 added to PortableApps menu. Handles reassembling corrupted RAID arrays.

### Removed: 
* TeamViewer has been replaced by AnyDesk. Mostly for compatibility reasons and ease-of-use, but also because TeamViewer just flat-out SUCKS by comparison.

### Updated:
* Many PortableApps have been updated.
* Ventoy to v1.0.33 <-- (Bug fix version mostly, but adds persistence for Kali and Clonezilla, as well as adding support for Linux VHD files from different bootloaders such as rEFInd, GRUB2, Systemd-boot, and GRUB4DOS.)
* Mini Windows 10 was run through NTLite to enable Dark Mode, and use small taskbar icons to maximize available screen space. Boot.wim was also recompressed and made a tiny bit smaller.
* Edited the Windows 10 & Windows 8.1 recovery disc titles by adding "+MS DaRT" at the end, so people know they include the useful MS DaRT utilities.
* Google Chrome Portable x64 to v 88.0.4324.104
* HDAT2 to v7.1 [BIOS]
* Parted Magic to v2020.12.25 [UEFI]
* SystemRescue to v7.02 Beta 005 [UEFI]
* AOMEI Backupper to v6.3.0 [UEFI]
* AOMEI Partition Assistant to v9.1 [UEFI]
* NIUBI Partition Editor to v7.4 [UEFI]
* Acronis TrueImage to v2021 Build 35860 [UEFI]
* EaseUS Partition Master to v15.5 [UEFI]
* Macrium Reflect to v7.3.5550 [UEFI]
* MiniTool Partition Wizard to v12.3 [UEFI]
* MiniTool ShadowMaker to v3.6 [UEFI]
* MiniTool Power Data Recovery to v9.2 [UEFI]
* PassMark MemTest86 to v9.0 Beta 2 [UEFI]

### Menu Changes:
* Version info has been updated.
* Removed the holiday hat.
* Adjusted my signature to look proper on 1920x1080 resolutions or less, up from 1366x768.
* New wallpaper, since the holidays are over.

### Fixed:
* The Microsoft .NET regressions have been fixed, apparently the "assembly" folder accidentally got removed before the v20.12 release.
* Fixed an issue where Portable 7-Zip v20.02 alpha was being detected as v19.00 Rev 2, and now won't be asked to upgrade when updating the other PortableApps (unless a legit newer version comes out).
* Further improvements to overall system stability and other minor adjustments have been made to enhance the user experience.
</details>

<details markdown="block">
<summary>Version 20.12</summary>

Changelog for v20.12:
---

### Added:
* Discord Portable has been added to the PortableApps menu. You can now keep in touch with friends and family alike! (And it auto-updates itself upon launch!)
* BootIt Bare Metal v1.69 [BIOS] added to the Boot_Repair directory.
* My newest standalone creation "Jayro's Lockpick" is joining MediCat USB! It takes every Password Reset boot disk for resetting Windows user accounts and combines them all into one simple and easy to use WinPE boot disc. You're presented with a simple menu, with all the best password reset tools at your disposal once it's fully booted. Note: "Passcape Reset Windows Password" is packaged a little differently, so it takes longer to load than the rest... Please be patient with it.
* Easy Translator to PortableApps menu, Accessibility section.

### Removed: 
* AOMEI Backupper PortableApp. It was redundant to the bootable WinPE version already on the USB. That's an additional 500+MB of disk space reclaimed.
* "PCUnlocker", "Passcape Reset Windows Password", and "Active@ Password Changer" were all removed in favor of "Jayro's Lockpick", as mentioned above. They all reside in there now.

### Updated:
* Ventoy to v1.0.30 <-- Added Password protection plugin.
* ShredOS is now password-protected as a safeguard, to prevent accidental launches. The password is "medicat" but without the quotes, and all lowercase letters. The password is shown on the menu entry itself, but you need to be set to 640x480 resolution or higher to read it. (Press [F5] to change screen resolutions)
* Minimum memory requirements have been reduced at the bottom of this changelog, to better reflect the memory needs of the included WinPE WIM files. Minimum RAM requirements below has dropped from 3GB down to 2GB, but you'll still want 4GB or more for comfortable usage. Luckily most modern PCs and laptops come with no less than 4GB these days.
* I actually downgraded the 2018 Malwarebytes Bootable WinPE to a 2016 version for added stability, it boots up WAY faster, uses much less RAM, and has a smaller file size. This older version is only temporary, until I have the time to build a proper one that's more up to date.
* New driverpacks for Snappy Driver Installer, and the driverpacks have been reoptimized by me from 2.48GB, down to just 638MB. Removing all the useless drivers for NT x86+x64, XP x86+x64, Vista x86+x64, 7 x86+x64, 8 x86+x64, 8.1 x86+x64 and 10 x86 cleaned up a bit more disk space for us, keeping just the 10 x64 drivers. They are still located at /PortableApps/Snappy Driver Installer/Drivers if you need to edit them further.
* I ran Mini Windows 10 through NTLite for a few settings changes and optimizations.
* Malwarebytes virus definitions to v2020.12.21.01
* Macrium Reflect to v7.3.5365 [UEFI]
* Replaced "Active@ Boot Disk" with "Active@ Data Studio" because it has more to offer, and updated it to  v17.0.0 [UEFI]
* Acronis True Image to v2021 build 34340 [UEFI]
* Acronis Cyber Backup to v12.5 Build 16386 [UEFI]
* Acronis Disk Director 12.5 build 163 [UEFI] is now the English version. Thanks to @Chansm on GBAtemp for the heads-up!
* EaseUS Partition Master to v15.0 [UEFI]
* NIUBI Partition Editor to v7.3.7 [UEFI]
* Rescuezilla to v2.1 64bit [UEFI] (groovy 20.10 version)
* Windows 10 Recovery disc updated to v10.0.19041.572 (Still includes MS DaRT)
* Windows 8.1 Recovery disc updated to include MS DaRT.

### Menu Changes:
* Version info has been updated.
* Changed the color of the F-keys to black, as the white blended into the light background.
* Added a cool drop-shadow to my name at the bottom.
* Squashed a bug in the 2016 Malwarebytes WinPE, where the Malwarebytes Web Access Control driver was causing issues when launching Malwarebytes Portable. The log file told me the exact file was X:\Windows\System32\drivers\mwac.sys, apparently. It's been removed, and I haven't had any more issues opening the app.
* Changed the NVMe drive logo to match the logo on front page of the MediCat USB thread on the forum.

### Fixed:
* Moved O&O BlueCon to the "Boot_an_Operating_System" folder where it fits in better, since it's a WinPE toolbox.
* Further improvements to overall system stability and other minor adjustments have been made to enhance the user experience.
</details>

<details markdown="block">
<summary>Version 20.11</summary>

Changelog for v20.11:
---

Added:
* Dual-mode "Boot Conf Replace" plugin has been added to of ventoy.json, so you can override the Linux config files with your own, instead of having to rebuild the ISO each time you update. The default example script was pasted in, and can be edited to your liking. I left it intact so it can be used as a reference. Read this to know more: https://www.ventoy.net/en/plugin_bootconf_replace.html
* "Persistence" plugin has been added to ventoy.json, so you can have persistence files going to your bootable Linux distros. The default example script was pasted in, and can be edited to your liking. I left it intact so it can be used as a reference. Read this to know more: https://www.ventoy.net/en/plugin_persistence.html
* "Injection" plugin has been added to ventoy.json, so you can inject some files (e.g. drivers/scripts, etc) into the runtime envrioment after boot.
  For Windows, that's the WinPE envrioment. For Linux, that's the initramfs envrioment. The default example script was pasted in, and can be edited to your liking. I left it intact so it can be used as a reference. Read this to know more: https://www.ventoy.net/en/plugin_injection.html
* "Auto Install" plugin has been added to ventoy.json, so you can use a setup script like "windows_unattended1.xml" or "ubuntu_server.seed" for example, instead of having to rebuild the ISO each time you update. The default example script was pasted in, and can be edited to your liking. I left it intact so it can be used as a reference. Read this to know more: https://www.ventoy.net/en/plugin_autoinstall.html
* "Linux vDisk Boot" plugin has been added to ventoy_grub.cfg, so you can use the F6 GRUB menu to boot your fixed-size Linux disk file. (VHD, VDI, and RAW formats are supported. VHDX and dynamic disks are not supported.). The default example script was pasted in, and can be edited to your liking. I left it intact so it can be used as a reference. Read this to know more: https://www.ventoy.net/en/plugin_vtoyboot.html
* "DUD (Driver Update Disk)" Plugin has been added to ventoy.json. Some linux distros provide a DUD mechanism. Give a Driver Update Disk image file and set some boot option during boot. Then the driver can be installed before disk scan. And hardware manufacturers generally also provide DUD images that conform to the corresponding distro requirement. The default example script was pasted in, and can be edited to your liking. I left it intact so it can be used as a reference. Read this to know more: https://www.ventoy.net/en/plugin_dud.html
* Active Password Changer Ultimate v11.0 [UEFI] added to the Password Removal folder.
* Acronis Disk Director v12.5 [UEFI] added to the Partition Tools folder.
* Active UNERASER v16.0.2 [UEFI] added to the Partition Tools folder.
* ShredOS v20200418 [UEFI] added to the Partition Tools folder.

Removed: 
* Many outdated and redundant apps in the Start Menu (Programs folder on the USB) were removed, due to already being in my PortableApps menu, and some were flat-out MOVED to the PortableApps menu for better accessibility. This shaved off a few hundred Megabytes.
* DBAN v2.3.0 ==> It has been replaced by it's successor ShredOS v20200418, which can boot from UEFI.

Updated:
* Ventoy to v1.0.29
* Malwarebytes virus definitions to v2020.11.22.05
* EasyUEFI to v4.5 [UEFI]
* Macrium Reflect to v7.3.5321 [UEFI]
* DiskGenius to v5.3.0.1066 [UEFI]
* AOMEI Backupper to v6.2.0 [UEFI]
* AOMEI Partition Assistant to v9.0 [UEFI]
* MiniTool Power Data Recovery to v9.1.1 [UEFI]
* SystemRescue to v7.0.1 [UEFI]
* You no longer have to mess with partition resizing! Just create a Ventoy-bootable USB using Ventoy2Disk, format the USB to NTFS, and then unzip the .001 file to the root of the drive. That's it!

Menu Changes:
* New square-shaped icons have been added, with rounded corners.
* Added { "VTOY_TREE_VIEW_MENU_STYLE": "1" } to the ventoy.json file, which gets rid of the [DIR] tabs and ISO file sizes. Looks much cleaner.
* Made the arrows on the Main Menu match Ventoy's arrows.
* Made new icons for all the .ISO, .WIM, and .EFI files in each menu. (Took about 5 hours of repetitive work.) Lots of unused icons in there as well for you to use if you'd like. Many of them are operating system icons.
* Moved MediCat USB version info to the bottom left corner.
* Re-made the MemTest86 icon. It looked like trash, and now isn't a blurry pixelated mess anymore. The pins have defined gold theeth, the chips are more defined, and has more refined edges.
* Added in a "back" button icon called vtoyret.png, thanks to Longpanda's advice. (@Ventoy on GBAtemp)
* New icon dock for the F1 through F6 keys, with icons. Many hours of testing and experimenting went into this major change, but it finally scales well with all resolutions without over-crowding and overlapping each other, even at 640x480.
* All these cool changes required a new badass wallpaper.

Fixed:
* You can now have spaces in your bootable ISO/WIM/EFI filenames.
* Further improvements to overall system stability and other minor adjustments have been made to enhance the user experience.
</details>