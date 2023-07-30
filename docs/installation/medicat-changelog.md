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