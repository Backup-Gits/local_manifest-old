# Mi A2 Lite (daisy) Manifest

I'm integrated stable sources in this local manifest. You can use copying into ./repo/local_manifests.

# Shortcut to be faster:

DT: https://github.com/TogoFire/device-xiaomi-daisy

VT: https://github.com/acras01/android_vendor_xiaomi_daisy

https://github.com/lupesoltec/vendor_xiaomi_daisy/tree/daisy-ten

https://github.com/TogoFire/android_vendor_xiaomi_daisy

https://github.com/mahajant99/vendor_xiaomi_sakura

https://github.com/a-huk/vendor_xiaomi_daisy

KT: https://github.com/Aarqw12/kernel_reborn

https://github.com/PixysOS-Devices/kernel_xiaomi_msm8953-sakura/

https://github.com/lupesoltec/kernel_loki/tree/4.9.222

MiuiCam: https://github.com/TogoFire/vendor_MiuiCamera

ExclusivePack: https://github.com/TogoFire/vendor_ExclusivePack


git clone https://github.com/TogoFire/tree_device_xiaomi_daisy -b xtended device/xiaomi/daisy

git clone https://github.com/Aarqw12/kernel_reborn -b LA.UM.8.6.2.r1/daisy kernel/xiaomi/daisy

git clone https://github.com/TogoFire/vendor_MiuiCamera -b ten vendor/xiaomi/MiuiCamera

git clone https://github.com/TogoFire/vendor_ExclusivePack -b master vendor/xiaomi

git clone https://github.com/acras01/android_vendor_xiaomi_daisy -b ten vendor/xiaomi/daisy

git clone https://github.com/lupesoltec/kernel_loki -b 4.9.222 kernel/xiaomi/daisy

git clone https://github.com/PixysOS-Devices/kernel_xiaomi_msm8953-sakura -b ten kernel/xiaomi/daisy

mv kernel/xiaomi/daisy/arch/arm64/configs/sakura_defconfig kernel/xiaomi/daisy/arch/arm64/configs/daisy_defconfig

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

# Extras

FaceUnlock:

git clone https://github.com/??? -b q external/motorola/faceunlock

https://github.com/BlissRoms/platform_manifest/commit/c582911a7065d98c5faee4e59409e2da9b6046aa    - YourRom/manifest

https://github.com/BlissRoms/platform_vendor_bliss/commit/fd23c675fab277d9ae3c7a09b217b989826f9d39   -vendor/YourROM/config/common.mk 

https://github.com/BlissRoms/platform_frameworks_base/commit/8c2c777a95f086078fc82a0c59dba705ddfb9132   -YourROM/frameworks/base

https://github.com/BlissRoms/platform_packages_apps_Settings/commit/519ca1d10b6c976b51afb82e61839f8979f19568   - YourRom/packages/apps/Settings

git fetch https://github.com/BlissRoms/platform_manifest.git && git cherry-pick c582911a7065d98c5faee4e59409e2da9b6046aa

git fetch https://github.com/BlissRoms/platform_vendor_bliss.git && git cherry-pick fd23c675fab277d9ae3c7a09b217b989826f9d39

git fetch https://github.com/BlissRoms/platform_frameworks_base.git && git cherry-pick 8c2c777a95f086078fc82a0c59dba705ddfb9132

git fetch https://github.com/BlissRoms/platform_packages_apps_Settings.git && git cherry-pick 519ca1d10b6c976b51afb82e61839f8979f19568

DolbyDigitalPlus:

git fetch https://github.com/TogoFire/android_vendor_xiaomi_daisy && git cherry-pick 586088c496b6dfd8d6248b5c517d6dc19e6ca611

https://github.com/TogoFire/android_device_xiaomi_daisy/commit/83807e72361c467e3d073984fcf7fb089671559a

https://github.com/TogoFire/vendor_ExclusivePack/blob/80f5667a89553135bb4156f3120d2d08b02d62bb/ExclusivePack/config.mk#L24

Source: https://forum.xda-developers.com/android/software/mm-p-dolby-digital-plus-arise-20181115-t3868192

Camera2:

git clone https://github.com/LineageOS/android_packages_apps_Camera2 packages/apps/Camera2

https://github.com/TogoFire/android_device_xiaomi_daisy/blob/fcfe6b0b1bbe6f15f0db67736ae5521a717764d0/device.mk#L160

Volume control style miui:
https://github.com/TogoFire/frameworks_base/commit/52edef18b20ba981a34ad46153505d4719c04dc5

git fetch https://github.com/TogoFire/frameworks_base && git cherry-pick 52edef18b20ba981a34ad46153505d4719c04dc5

Channel: https://t.me/XtendedDaisy


# Credits

[@lupesoltec](https://github.com/lupesoltec) - LupeSolTec

[@acras01](https://github.com/acras01) - Acras

[@TogoFire](https://github.com/TogoFire) - Togo77

[@ZIDAN44](https://github.com/ZIDAN44) - ZIDAN44

[@vmanoel00](https://github.com/vitor00almei) - Vitor


# and all of daisy devs... :)
