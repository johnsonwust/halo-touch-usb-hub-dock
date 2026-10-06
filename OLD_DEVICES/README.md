# Old Device Firmware And Resource Package

This package is for older devices such as God Eye, Taiji Pi, iCRT secondary display, Fuxuan Necklace, and related ESP32-based devices.

Original download group:

- God Eye, Taiji Pi, and older devices: https://pan.baidu.com/s/1iLHPFT_hSM2iqW_l15aJeQ?pwd=mpr2
- Extraction code: `mpr2`

The newer Bluetooth knob and Taiji View Pi series are stored separately in the main repository package.

## Directory Guide

- `ESP32_ORIGINAL_XIAOZHAZHA_V1.2`: original ESP32 firmware reference and flashing note.
- `ICRT_SECONDARY_DISPLAY`: iCRT secondary display tools, AIDA64 files, MJPEG converter, and city code table.
- `FLASHING_TOOLS`: flashing tools. Files ending in `.baiduyun.p.downloading` are incomplete Baidu Netdisk downloads.
- `CUSTOM_FIRMWARE`: custom firmware binaries.
- `MINI_GOD_EYE_PC_HOMEKIT`: Mini God Eye PC/HomeKit N8R2 boot files. Files ending in `.baiduyun.p.downloading` are incomplete Baidu Netdisk downloads.
- `MINI_GOD_EYE_PC_HOMEKIT_N8R8`: Mini God Eye PC/HomeKit N8R8 firmware files and notes.
- `WALL_SWITCH_86_BOX`: 86 wall switch firmware files.
- `FUXUAN_NECKLACE`: Fuxuan Necklace firmware, BOM, and quick guide.
- `CLOCK_FACES_240X240_ROUND`: 240 x 240 round-screen clock face resources.
- `CLOCK_FACES_240X240_SQUARE`: 240 x 240 square-screen clock face resources.
- `CLOCK_FACES_480X480_ROUND`: 480 x 480 round-screen clock face resources.

## General Operation Notes

- Devices that need Wi-Fi create an access point after power-on, such as `My-Ap`, `Crt-Ap`, `Mirror-Ap`, or `Box-Ap`.
- The default AP password is `12345678`.
- If the setup page does not open automatically, open `http://192.168.4.1` in a browser.
- Button devices usually use long press for menu/confirm and short press for next item.
- Touch devices usually open the menu by swiping up. Swipe left or right to switch items inside supported apps.
- AIDA64 Remote Sensor setup should keep the original `Show Label` text and set `Show unit` to `^`.
- MJPEG and JPG files should match the target screen resolution.
- NES ROM files, where supported, should use ASCII names and be placed in the root `NES` directory.

## Reference

- Original Chinese guide: https://pressf5.run/?p=119
