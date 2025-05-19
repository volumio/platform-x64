
## **platform-x64**

### **Tracking from bookworm 10.05.2025**

|Date|Author|Change
|---|---|---|
|20241204|gkkpch|Initial Kernel 6.6.32
|20241205||Bumped to Kernel 6.12.1 for bookworm testing
|20241208||Reversed to 6.6.y due to regression
|20241210||x86_amd64.tar.xz: used modified bytcr-init.sh 
|||Kernel updated to 6.6.65
|20241219||x86_amd64.tar.xz: used improved bytcr_init.sh and jackdetect.sh
|20250102||Fixed initial headphone/speaker switch in bytcr_init.sh
|20250108||[snd-usb-audio] Add DSD quirk for Luxman DA-250
|||Kernel updated to 6.6.69
|20250510|foonerd|Kernel updated to 6.12.28
|20250513|foonerd|Realtek rtw88 from upstream
|20250514|foonerd|[i915] missing KMS dependencies
|20250516|gkkpch|[hda-intel sound init] add Realtek ALC663 and ALC897
||foonerd|[wifi] Restore 88XXAU USB driver module
|||[wifi] Add runtime unblock mechanism for rfkill
|||[cifs] Enable SMB311 and SMB_DIRECT for high-performance NAS access
|||[cifs] Allow legacy SMB1 shares
|||[HID] Devices twaks - regression
|20250519|fooner|Bluetooth and LPSS support for Gemini Lake platforms
|||Kernel updated to 6.12.29
