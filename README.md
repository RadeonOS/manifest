### RadeonOS

This is the manifest for RadeonOS

To sync and build

-> repo init -u https://github.com/RadeonOS/manifest.git -b 6

-> repo sync ( if on slower network then repo sync -f -j1 )

-> source build/envsetup.sh

-> lunch aosp_sprout4-userdebug

-> make -j$(nproc) otapackage
```

Note -> ATM, this will only be buildable on Linux systems, not darwin
