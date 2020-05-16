# Mi A2 Lite (daisy) Manifest

I'm integrated stable sources in this local manifest. You can use copying into ./repo/local_manifests.

# Shortcut to be faster:

DT: https://github.com/TogoFire/device_xiaomi_daisy

VT: https://github.com/lupesoltec/vendor_daisy

https://github.com/TogoFire/vendor_daisy

KT: https://github.com/Aarqw12/kernel_reborn

https://github.com/TogoFire/kernel_reborn

https://github.com/PixysOS-Devices/kernel_xiaomi_msm8953-sakura/

https://github.com/lupesoltec/kernel_loki/tree/4.9.222

MiuiCam: https://github.com/TogoFire/vendor_MiuiCamera

ExclusivePack: https://github.com/TogoFire/vendor_ExclusivePack


git clone https://github.com/TogoFire/device-xiaomi-daisy -b xq device/xiaomi/daisy

git clone https://github.com/Aarqw12/kernel_reborn -b LA.UM.8.6.2.r1/daisy kernel/xiaomi/daisy

git clone https://github.com/TogoFire/vendor_MiuiCamera -b ten vendor/xiaomi/MiuiCamera

git clone https://github.com/TogoFire/vendor_ExclusivePack -b master vendor/xiaomi

git clone https://github.com/lupesoltec/vendor_daisy -b ten vendor/xiaomi/daisy

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

https://github.com/TogoFire/device-xiaomi-daisy/commit/20ef362ef25ae7167a22d67851cc1c8d9effb8e9

https://github.com/TogoFire/vendor_ExclusivePack/blob/80f5667a89553135bb4156f3120d2d08b02d62bb/ExclusivePack/config.mk#L24

Source: https://forum.xda-developers.com/android/software/mm-p-dolby-digital-plus-arise-20181115-t3868192

Camera2:

git clone https://github.com/LineageOS/android_packages_apps_Camera2 packages/apps/Camera2

https://github.com/TogoFire/device-xiaomi-daisy/blob/0190fd3be3f58863b49eac53af84c0a24ea59f86/device.mk#L160

Volume control style miui:
https://github.com/TogoFire/fwb-xq/commit/500cc88f09f11b9606aca1f8f1db4e12e214ea0d

git fetch https://github.com/TogoFire/fwb-xq xqm && git cherry-pick 500cc88f09f11b9606aca1f8f1db4e12e214ea0d

ScreenShot: https://t.me/XtendedDaisy/142

Volume controu sylte IOS and Miui:
https://github.com/TogoFire/fwb-xq/commit/701b7a7dad73f76078937c24735ff2012807f811

git fetch https://github.com/TogoFire/fwb-xq xq-rvd && git cherry-pick 701b7a7dad73f76078937c24735ff2012807f811

ScreenShot: https://t.me/XtendedDaisy/179

Channel: https://t.me/XtendedDaisy


# Credits

[@lupesoltec](https://github.com/lupesoltec) - LupeSolTec

[@acras01](https://github.com/acras01) - Acras

[@TogoFire](https://github.com/TogoFire) - Togo77

[@ZIDAN44](https://github.com/ZIDAN44) - ZIDAN44

[@vmanoel00](https://github.com/vitor00almei) - Vitor


# and all of daisy devs... :)
