# IN TESTING!!!

# Opencore Dell-Precision-5540

<img width="1521" alt="Monterey" src="https://user-images.githubusercontent.com/40405226/227790654-6b96b1a6-df8e-4dbe-963e-7be5f921f3dc.png">



## Configuration

| Specifications | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Computer model      | Dell Precision 5540      |
| Processor           | Intel Core i9-9980HK cofee lake  |
| Memory              | 32GB (2x16gb) 2666MMHz upgradable to 64GB |
| NVME                | M.2 Nvme KINGSTON SNV2S1000G Media 1TB 
| Triple Boot         |512GB For MACOS 256gb for UBUNTU 256gb for Windows|
| Integrated Graphics | Intel UHD Graphics 630                     |
| Monitor             |4k 3840x2160 touchscreen (15.6") |
| Sound Card          | Realtek alc3266 (ALC298)          |
| Wireless Card       | Intel AC9260 |

## Misc before install:
- Unlock CFG: 
- https://www.reddit.com/r/Dell/comments/fzv599/xps_7590_160_uefi_unlock_undervolting_and_remove/
- Extracted file sct.txt

## Current Status

- **Fingerprint sensor is not working (never will work)**
- Everything else works well except Airdrop, right mouse click
- Ensure to edit the **config.plist** and add valid  **PlatformInfo Generic** and **SMBIOS** values

## Triple Boot with refind
- i can't boot windows and ubuntu from OC picker.
- install refind in Tools.zip
- Replace installed refind folder with refind in OC_0.9 folder for minimal theme.

## Misc after install:
- [Enable HiDPI](https://github.com/xzhih/one-key-hidpi) :
- And RDM app in tools folder  https://github.com/avibrazil/RDM
