---------------------------------------------------------------------------------------
 Getting Started:
 ==============

To get started with TCW OS, building for testing purpose.

```bash
repo init -u https://github.com/tcwghub/tcw_ROM_Manifest -b 11

```

Then to sync up:

```
repo sync -c -f --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j8
```

---------------------------------------------------------------------------------------
 Compilation of OctaviOS:
 ==================

From root directory of Project, perform following commands in terminal

```bash
$ . build/envsetup.sh
$ lunch octavi_$device-userdebug
$ brunch <device_codename>
```
---------------------------------------------------------------------------------------
 Credits:
 =======

 * [**LineageOS**](https://github.com/LineageOS)
 * [**RevengeOS**](https://github.com/RevengeOS)
 * [**POSP**](https://github.com/PotatoProject)
 * [**AOSiP**](https://github.com/AOSiP)
 * [**DotOS**](https://github.com/DotOS)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**Havoc-OS**](https://github.com/Havoc-OS)
 * [**Xtended**](https://github.com/Project-Xtended)
 * [**ColtOS**](https://github.com/Colt-Enigma)
