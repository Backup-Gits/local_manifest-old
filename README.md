# Mi A2 Lite (daisy) Manifest

I'm integrated stable sources in this local manifest. You can use copying into ./repo/local_manifests.

# Shortcut to be faster:

DT: https://github.com/TogoFire/device_xiaomi_daisy

VT: https://github.com/lupesoltec/vendor_daisy

https://github.com/TogoFire/vendor_daisy

https://github.com/lupesoltec/vendor_xiaomi_daisy

https://github.com/TogoFire/vt_xiaomi_daisy

KT: https://github.com/RebornDaisyProject/lineage_msm8953

https://github.com/PotatoDevices/kernel_xiaomi_daisy/

https://github.com/TogoFire/lineage_msm8953

https://github.com/RebornDaisyProject

https://github.com/TogoFire/kernel_reborn

https://github.com/PixysOS-Devices/kernel_xiaomi_msm8953-sakura/

https://github.com/lupesoltec/kernel_loki/tree/4.9.222

MiuiCam: https://github.com/TogoFire/vendor_MiuiCamera

ExclusivePack: https://github.com/TogoFire/vendor_ExclusivePack


git clone https://github.com/TogoFire/device-xiaomi-daisy -b xq device/xiaomi/daisy

git clone https://github.com/TogoFire/vendor_daisy -b ten vendor/xiaomi/daisy

git clone https://github.com/TogoFire/lineage_msm8953 -b daisy kernel/xiaomi/daisy

git clone https://github.com/PotatoDevices/kernel_xiaomi_daisy -b croquette-release kernel/xiaomi/daisy

git clone https://github.com/TogoFire/kernel_reborn -b LA.UM.8.6.2.r1/daisy kernel/xiaomi/daisy

git clone https://github.com/TogoFire/vendor_ExclusivePack -b master vendor/xiaomi

git clone https://github.com/lupesoltec/kernel_loki -b 4.9.222 kernel/xiaomi/daisy

git clone https://github.com/PixysOS-Devices/kernel_xiaomi_msm8953-sakura -b ten kernel/xiaomi/daisy

mv kernel/xiaomi/daisy/arch/arm64/configs/sakura_defconfig kernel/xiaomi/daisy/arch/arm64/configs/daisy_defconfig

mv kernel/xiaomi/daisy/arch/arm64/configs/sleepy_defconfig kernel/xiaomi/daisy/arch/arm64/configs/daisy_defconfig

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>


BUILDTYPE:

user -	Limited access; suited for production;  User build is the one flashed on production phones. Has no root access.

userdebug	 - Like user but with root access and debug capability; preferred for debugging; User debug build does not come with default root access but can be rooted. It also contains extra logging.

eng	Development -  configuration with additional debugging tools; Engineering build comes with default root access.

Sources: https://source.android.com/setup/build/building

https://source.android.com/setup/develop/new-device

https://stackoverflow.com/questions/13950589/difference-between-eng-and-user-debug-build-in-android

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

git fetch https://github.com/BlissRoms/platform_packages_apps_Settings.git q-backup && git cherry-pick 519ca1d10b6c976b51afb82e61839f8979f19568

DolbyDigitalPlus:

git fetch https://github.com/TogoFire/android_vendor_xiaomi_daisy && git cherry-pick 586088c496b6dfd8d6248b5c517d6dc19e6ca611

https://github.com/TogoFire/device_xiaomi_daisy/commit/20ef362ef25ae7167a22d67851cc1c8d9effb8e9

https://github.com/TogoFire/vendor_ExclusivePack/blob/80f5667a89553135bb4156f3120d2d08b02d62bb/ExclusivePack/config.mk#L24

Source: https://forum.xda-developers.com/android/software/mm-p-dolby-digital-plus-arise-20181115-t3868192

Camera2 for Xiaomi Devices (green cam fix):

git clone https://github.com/TogoFire/android_packages_apps_Camera2 packages/apps/Camera2

Volume control style miui:
https://github.com/TogoFire/fwb-xq/commit/500cc88f09f11b9606aca1f8f1db4e12e214ea0d

git fetch https://github.com/TogoFire/fwb-xq xqm && git cherry-pick 500cc88f09f11b9606aca1f8f1db4e12e214ea0d

ScreenShot: https://t.me/XtendedDaisy/142

Volume control sylte IOS and Miui:
https://github.com/TogoFire/fwb-xq/commit/701b7a7dad73f76078937c24735ff2012807f811

git fetch https://github.com/TogoFire/fwb-xq xq-rvd && git cherry-pick 701b7a7dad73f76078937c24735ff2012807f811

ScreenShot: https://t.me/XtendedDaisy/179

# Commit correctly

Authorship:
```bash
git status
```

```bash
git add *
```

```bash
git commit -m 'your text'
```

```bash
git commit --amend --author "Author <email@address.com>"
```

```bash
Co-Authored-By: Author <email@address.com> 
```    
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

DELETE COMMIT:
```bash
git log (to see the commit and its hashes).
``` 
Let's tag our last commit with a tag, so we can find it after removing commits:

```bash
git tag    (some word from the last commit. Or any words from the commit that you want to be deleted)
```
```bash
git reset --hard [target commit hash] - Here you put what you want your last commit to be.
```

```bash
git push -f   (to force the push)
```

REVERT: 
```bash
git revert SHA
```
Example: git revert 9b99bb1bb6bdad80d6765d9a1175587600ae496e

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>


CHANGE COMMIT DATE:

It is important to give authorship to the author of the commit, and it is also very important that the exact date, time and day are also present.

Logic: https://gist.github.com/TogoFire/ec177f4fbf4776c6d5bb69e66bd2ba5d
```bash
git rebase <commit-hash>^ -i
```
```bash
GIT_COMMITTER_DATE="$(date)" git commit --amend --no-edit --date "$(date)"
```

Example:
```bash
git commit --amend --no-edit --date "Fri, 07 Feb 2017 22:47:00 +0300"
```
To find out the exact date and time of the author, put ".patch" at the end of the site, example:
https://github.com/PixelExperience-Devices/device_xiaomi_lavender/commit/579accf69859b5100f04426ade2ad6d3cf7d8b40.patch

Sources:

https://codewithhugo.com/change-the-date-of-a-git-commit/

https://gist.github.com/ythecombinator/7e70d7baea74305c93e6

https://garysferrao.github.io/git/commit/date/2015/12/01/change-git-commit-date.html

https://stackoverflow.com/questions/454734/how-can-one-change-the-timestamp-of-an-old-commit-in-git

https://confluence.atlassian.com/bitbucketserverkb/how-do-you-make-changes-on-a-specific-commit-779171729.html

# GCC
GCC Library:
https://github.com/TogoFire/gcc_library

The recommended for Daisy is: Linaro GCC 4.9-2017.01 Release

# DENIALS/SEPOLICY

Script: https://github.com/TogoFire/selinux-denial-fixer

python denials.py
(DON'T FORGET CREATE FILE "denials.txt"

Make a txt called denials.txt and place your denials in them after that open a terminal in that directory and run this:
python denials.py

Your denials will be fixed and placed in fixes.txt)


Get log. Commands:

dmesg -w | grep avc: > /sdcard/denials.txt

dmesg > /sdcard/dmesg.txt

logcat -d -f /sdcard/logcat.txt

LOGIC:
scontext = file

tcontext-> object_r = object

tclass = class

allow (scontext) (tcontext) :( tclass) {action}

Sources: https://msfjarvis.website/posts/understanding-and-resolving-selinux-denials-on-android/
https://github.com/baalajimaestro/selinux-denial-fixer

# Chat & Channels: 

https://t.me/TogoFireWork

https://t.me/LuPeSolTec_Work

https://t.me/A2LiteOfficial

https://t.me/TogoFireChannel

https://t.me/LuPeS0lTec


# Credits

[@lupesoltec](https://github.com/lupesoltec) - LupeSolTec

[@TogoFire](https://github.com/TogoFire) - Togo77

[@vmanoel00](https://github.com/vitor00almei) - Vitor


# and all of daisy devs... :)
