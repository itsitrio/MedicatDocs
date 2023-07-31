---
title: VHD Changelog
layout: default
parent: Installation
nav_order: 99
---

<details markdown="block">
<summary>Version 21.06 VHD</summary>


Changelog for v21.06 VHD:
----

### Added:
* Discord
* All Visual C++ Redistributables (2005 - 2019)
* Dot Net Framework v6.0.0 Preview 5
* VLC Player x64 v3.0.14
* 7-Zip x64 v21.02 aplha
* Notepad++ v8.1
* Google Chrome v91.0.4472.114 (Official x64) with uBlock Origin (ad blocker) installed.
* "Take Ownership" context menu registry entry.
* "Small Taskbar Icons" registry hack, since the taskbar for Windows 11 lacks the traditional "Use small taskber icons" in the settings.

### Removed: 
* Telemetry as much as possible, everything tweaked for performance and privacy to the best of my ability.
* Bloatware stripped out using NTLite. Leftover apps uninstalled manually after installation.
* Hibernation disabled.
* Pagefile disabled.
* System Restore disabled, but still functional if you want it back on again.

### Updated Apps and Changes:
* Jayro's Lockpick (updated by @AAA3A)
* Jayro's Toolbox is now a shortcut box in the Start Menu. Click it to open it and show the tool icons.
* Due to changes in Windows 11, I'm unable to make a God Mode shortcut on the Desktop. I had to seek out a new option, so God Mode is now pinned to the Start Menu. Open it, and it will list everything God Mode has to offer as shortcuts.
* The only drivers added were installed silently by Windows after installation. These are AMD chipset and APU drivers, and possibly others.

### Fixed:
* TPM 2.0 patched and working.
* Windows Update and the Microsoft Store are now working in this build.
* Removed bandwidth limitations.
* Further improvements to overall system stability and other minor adjustments have been made to enhance the user experience.

### Known issues:
* Middle-clicking an already open app in the taskbar doesn't open another instance of the running app like you'd think, this could just be a minor Windows regression. This was found out by Linus Sebastion on Linus Tech Tips, so props to him for discovering this bug.
* Once in a while a 'feature update' for handwriting stuff pops up trying to install and it will fail, and can be completely ignored as it's harmless. Just an annoying nag on occasion.
</details>

