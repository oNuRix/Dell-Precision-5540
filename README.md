# No more have this device!!!

# Opencore Dell-Precision-5540

![screenshot_001](https://user-images.githubusercontent.com/40405226/229776755-ba21fc9c-94c9-46a0-9695-fb90a63f5644.png)


## Configuration

| Specifications | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Computer model      | Dell Precision 5540      |
| Processor           | Intel Core i9-9980HK cofee lake  |
| Memory              | 32GB (2x16gb) 2666MMHz upgradable to 64GB |
| NVME                | M.2 Nvme KINGSTON SNV2S1000G Media 1TB 
| Triple Boot         |512GB For MACOS 256gb for UBUNTU 256gb for Windows|
| Integrated Graphics | Intel UHD Graphics 630 / NVIDIA Quadro T2000 Disabled      |
| Monitor             |4k 3840x2160 touchscreen (15.6") |
| Sound Card          | Realtek alc3266 (ALC298)          |
| Wireless Card       | Intel AC9260 |

## Misc before install:
- Unlock CFG: 
- https://www.reddit.com/r/Dell/comments/fzv599/xps_7590_160_uefi_unlock_undervolting_and_remove/
- Extracted file sec.txt

## Current Status

- **Fingerprint sensor is not working (never will work)**
- Everything else works well except Airdrop, right mouse click on Monterey.
- Headsphone mic, thunderbolt doesn't work.
- Wifi , Bluetooth issue on Ventura.
- Fix (if can't turn on) for bluetooth: sudo pkill bluetoothd , for wifi: sudo pkill wifi 
- Ensure to edit the **config.plist** and add valid  **PlatformInfo Generic** and **SMBIOS** values.
- Find your's screen IODisplayedid in ioreg and add AAPL00,override-no-connect in deviceProperties.

## Triple Boot with refind
- i can't boot windows and ubuntu from OC picker.
- install refind in Tools.zip
- Replace installed refind folder in EFI with refind folder in OC_0.9 folder for minimal theme.
- https://chriswayg.gitbook.io/opencore-visual-beginners-guide/advanced-topics/dual-boot-options/create-refind-booter

## Misc after install:
- [Enable HiDPI](https://github.com/xzhih/one-key-hidpi) :
- And RDM app in tools folder  https://github.com/avibrazil/RDM
