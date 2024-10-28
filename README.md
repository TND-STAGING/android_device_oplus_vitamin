# Android device tree for Oplus Nord 3 (vitamin)

# How-to compile it:

 - twrp-12.1 Manifest
```
    repo init --depth=1 -u https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp.git -b twrp-12.1
```
 - Sync
```
    repo sync
```
 - Clone TheNoobDevs-Staging twrp tree
```
    git clone https://github.com/TND-STAGING/android_device_samsung_gta9.git -b twrp-14 device/samsung/gta9
```
 - Prepare
```
    export ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch twrp_vitamin-eng
```
 - Run the Build Command
```
    mka vendorbootimage
```
# Contributors
