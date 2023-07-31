---
title: Installing Medicat VHD
layout: default
#parent: Installation
nav_order: 2
last_modified_date: March 29, 2023
---
# Installing Medicat VHD

{: .note }
This website is being built with the documentation from the old Docs site.

Medicat VHD is a VHD file containing a system created from Windows 11. It is 30GB in size with 13GB of free space.
To run it, USB 3.0 is STRONGLY recommended as a bare minimum, with USB 3.2 Gen 2 being highly advisable!
MediCat VHD is NOT a Win10PE like Mini Windows 10. It is a full Windows 10 installation for PC repair, which uses the real hardware of your computer. It is much less limiting in terms of functionality.
Once started, customize it as much as you want like a real windows. All changes will be saved... You can now do your actions in a much less limited way.

<details markdown="block">
<summary>Installing on Medicat USB</summary>
Extract ONLY the VHD folder to the MediCat USB drive, and make sure you have 20GB of free space. a minimum of 64GB USB 3.0 drive is required.

{: .warning }
Extracting the entire .zip file's contents to a MediCat USB drive will cause it to autoboot into MediCat VHD EVERY TIME. So use caution!

</details>

<details markdown="block">
<summary>Installing Standalone</summary>
Install Ventoy and then extract all the contents to the root of the drive, and you're good to go!

</details>

<details markdown="block">
<summary>Installing on an IODD</summary>

Browse into the VHD folder of the zip, and extract the [UEFI]_MediCat_VHD_&DW.vhd file into your iODD's _ISO folder, and mount it. And NEVER defrag the VHD, or you may face corruption! I recommend defragging the iODD drive BEFORE adding the VHD to it. This will mitigate any chance of the VHD giving you the "DEFRAG" warning on the iODD's screen. 


Notes: The "&DW" at the end of the VHD file tells the iODD drive that the VHD is read/write. Removing that will cause problems, so just leave it alone.Supported iODD enclosure models are the iODD 2531, iODD 2541, and the iODD mini.

</details>