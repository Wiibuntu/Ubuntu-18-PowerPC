# Ubuntu-18-PowerPC
Ubuntu 18 built for 32 bit PowerPC Mac Machines. This version IS NOT built for the Nintendo Wii.

![alt text](https://github.com/Wiibuntu/Ubuntu-18-PowerPC/blob/main/Ubuntu%2018%20Screenshots/Screenshot_2024-07-21_17-29-01.png?raw=true)

![alt text](https://github.com/Wiibuntu/Ubuntu-18-PowerPC/blob/main/Ubuntu%2018%20Screenshots/Screenshot_2024-07-21_17-32-42.png)


# HOW TO INSTALL/BOOT

NOTE: I DO NOT HAVE A ACTUAL POWERPC MAC TO TEST THIS ON. THIS HAS BEEN TESTED ON EMULATION!

In the downloads section I have prodived the exact qemu disk image I used. Download that file and add to a 32bit powerpc VM.
Currently the provided boot partition DOES NOT BOOT! You need to allow "Direct Kernel Boot" in the "Boot Options" tab.
The kernel is provided in this git repo and the Initrd is provided below the download for the disk image file in the downloads section (only due to size).

In order to use this on real hardware you would need to install Ubuntu 16 and upgrade to 18 yourself using the link below thanking mechie for the hard work.

# SPECIAL THANKS TO MECHIE ON SOURCEFORGE!

This wouldnt have been possible without Mechie providing the repository needed to upgrade ubuntu 16 to 18. Mechie created a custom repo for Ubuntu upgrading and compiling the packages for 32 bit instead of 64 bit.

https://sourceforge.net/projects/powerpc-linux-builds/files/ubuntu-bionic-powerpc/
