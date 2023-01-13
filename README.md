# AMDVBFlash-ATI-ATIFlash
(https://github.com/MrFreemanConscience/AMDVBFlash-ATI-ATIFlash/blob/main/6_small-v1649492263.png?raw=true)

AMD AMDVBFlash is used to flash the graphics card BIOS. The version released by ATI was called ATIFlash or just WinFlash.

It supports all AMD Radeon graphics cards, like RX 6900 XT, RX 6800 XT, RX 6700 XT, RX 5700, RX 5600, RX 5500. You can also flash the BIOS for all AMD Radeon RX Vega, RX 580, RX 480, and all older ATI cards.

The AMDVBFlash BIOS update software runs under Windows.

AMD has changed the behavior of AMDVBFlash in newer versions. It now requires a constant running Ring-0 kernel-mode driver. This is a security risk, you really only need the driver for a few minutes while saving the BIOS or flashing. That's why AMDVBFlash 3.15 and newer include AMDVBFlashDriverInstaller.exe, which installs/uninstalls the AMD driver with one click. This software was written by us at TPU and is signed digitally with our signature.

Version History
---------------
3.31 (January 28th, 2022)
+ Added support for Navi 24 (RX 6500 XT, RX 6400 and others)

3.20 (June 7th, 2021)
+ Added support for Radeon RX 6900 XT XTXH

4.71 (May 20th, 2021)
+ Adds support to flash Radeon RX 6900 XT Navi 21 XTXH chips (device ID 73AF)

3.15 (April 19th, 2021)
+ Adds support for AMD Radeon RX 6700 XT, RX 6800, RX 6800 XT, RX 6900 XT
+ Adds AMDVBFlashDriverInstaller.exe, written by us at TPU, which lets you easily install/uninstall the AMD driver that's now required to execute flashing
