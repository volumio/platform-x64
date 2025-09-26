
## **platform-x64**

### **Tracking from bookworm 04.12.2024**


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
|||[cifs] Enable SMB311 and SMB_DIRECT for high-performance NAS access
|||[cifs] Allow legacy SMB1 shares
|||[HID] Devices twaks - regression
|20250519|foonerd|Bluetooth and LPSS support for Gemini Lake platforms
|||Kernel updated to 6.12.29
|20250520|gkkpch|ACPI fixes for fallback for brightness, mute, volume keys
|20250521|foonerd|Kernels build dependencies options
|20250522|gkkpch|Correct acpi button handling and optimization
|20250523|foonerd|Kernel updated to 6.12.30
|20250523|gkkpch|[ACPI] Add mute for bay-/cherrytrail soundcards, add screenshot move script
|20250704|gkkpch|[hda-intel soundcard init] Realtek ALC897: unmute all IEC958 controls
|||Created new platform-x64 repo branch 6.12.35
|20250919|gkkpch|[grub.cfg] Add "boot_screen_rotation.cfg" support
|20250925|gkkpch|[grub.cfg] Modified bootscreen rotation support
|||Kernel updated, new repo branch 6.12.49
|||Additional kernel params for gyro sensors and backlight support
|20250925|gkkpch|[grub.cfg] Corrected bootscreen rotation config location
