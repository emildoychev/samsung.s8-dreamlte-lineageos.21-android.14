Samsung S8 | dreamlte | LineageOS 21 (Android 14)

Install TWRP Recovery (only need to do once)

https://eu.dl.twrp.me/dreamlte/ 

twrp-3.7.0_9-0-dreamlte.img.tar | 38.7 MB | 2022-10-15

& no-verity-opt-encrypt-6.1.zip (only works on twrp-3.5.0_9-0-dreamlte.img.tar)

Boot into TWRP Recovery -> Wipe/Format -> Install

#1

https://ivanmeler.github.io/devices/dreamlte.html - Probably won’t get an update

https://github.com/ivanmeler/ota_provider/releases?q=dreamlte_lineage-21&expanded=true 

lineage-21.0-20240829-UNOFFICIAL-dreamlte.zip | 874 MB | 2024-08-29

#2

MindTheGapps-13.0.0-arm64 - probably not getting any more updates

https://github.com/MindTheGapps/14.0.0-arm64/releases/latest

MindTheGapps-14.0.0-arm64-20250203_200051.zip | 412 MB | 2025-02-03

or NikGapps-core-arm64 - probably not getting any more updates

https://sourceforge.net/projects/nikgapps/files/Releases/Android-14/

NikGapps-core-arm64-14-20260204-signed.zip | ?? MB | 2026-02-04

#3

https://github.com/topjohnwu/Magisk/releases

Magisk-v30.7.zip | 11.1 MB | 2026-02

Wipe Cache/Dalvik -> Reboot System -> Setup offline

Enable developer options

Stay awake = Enable

USB debugging = Enable

Advanced restart = Enable

Reboot -> Connect to Wi-Fi -> If Magisk doesn’t show to set up -> Install Magisk-v30.7.apk -> Open Magisk and setup, requires restart

From Magisk app -> Modules -> Install from storage PFLite -> Reboot

PFLite.MINIMAL.v2.0.P3XL.Android.13.zip

Now in Settings -> About it should say Model: Pixel 3 XL

Disable: Calculator, Calendar, Clock, Contacts, Gallery, Live Wallpaper Picker, Music, MusicFX, Recorder

Settings -> Display -> Screen timeout = 10min

Settings -> System -> Status bar -> Battery % = Next to the icon

Quick settings: Wi-Fi, Bluetooth | Quick Share, Battery Saver | Auto-Rotate, Airplane mode
