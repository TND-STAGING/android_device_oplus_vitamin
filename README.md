# Android device tree for Oplus Nord 3 (ossi)

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
    git clone https://github.com/TND-STAGING/android_device_oplus_vitamin.git -b twrp-12.1 device/oplus/ossi
```
 - Prepare
```
    export ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch twrp_ossi-eng
```
 - Run the Build Command
```
    mka vendorbootimage
```
# Contributors
[KO-HI-DEV](https://github.com/Ko-Hi-Dev)
