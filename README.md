# Rog-Strix-B460i Hackintosh
This is the hackintosh for the Rog-Strix-B460i

![Hackintosh](https://github.com/ccnoxx/hackintosh-Rog-Strix-B460i-EFI/blob/main/WechatIMG12.png?raw=true)

## SPECS

+ OS: macOS 11.4 20F71 x86_64 / (SMBIOS: iMac19,1)
+ OpenCore: 0.6.9
+ CPU: Intel i9-10900 (10c20t ES) @ 2.5GHz
+ iGPU: Intel UHD Graphics 630
+ dGPU: Asrock RX560 4G ITX
+ Wi-Fi: BCM94352Z
+ Case: LGK3S
+ Power: 750W 80 Plus PLATINUM [CORSAIR SF750](https://item.jd.com/100004003340.html)
+ SSD: 1TB [HIKVISION C2000Pro](https://item.jd.com/100007731034.html)
+ RAM: 16GB x 2 [Gloway DDR4 3000](https://item.jd.com/100003386093.html)
+ CPU Cooler: ID-COOLING [IS-6K](https://item.jd.com/100009286107.html)

## BIOS

**Disabled:**
- Fast Boot
- VT-d
- CSM
- Intel SGX
- CFG Lock (No option in BIOS, Asus B460 motherboards are factory unlocked)

**Enabled:**
- VT-x
- Above 4G decoding
- Hyper-Threading
- Execute Disable Bit
- EHCI/XHCI Hand-off
- OS type: Windows 8.1/10 UEFI Mode
- DVMT Pre-Allocated (iGPU Memory): 64MB

## What's working

- [x] Intel UHD630 (iGPU)
- [x] Asrock RX RX560 ITX (dGPU)
- [x] Restart/Shutdown
- [x] Sleep/Wake
- [x] Power Management (Native support)
- [x] WiFi & Bluetooth (BCM94352Z)
- [x] USB

## Before Using

- **_PLEASE ADD YOUR `SMBIOS` BEFORE USING_**

## CREDITS
- [corpnewt - corpnewt](https://github.com/corpnewt)
- [acidanthera](https://github.com/acidanthera)
- [xjn819 blog](https://blog.xjn819.com/)
