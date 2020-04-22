# DeskMini 310 Hackintosh

### Specs
+ macOS Catalina 10.15.4
+ OpenCore 0.5.7
+ DeskMini 310
+ Bios version 4.20
+ Intel core i3-8100
+ HyperX HX426S15IB2K2 16Gb kit
+ Crucial SATA MX500 250Gb
+ Fenvi BCM94360NG WiFi M.2 module

### Bios settings
+ Advanced > Chipset Configuration > Above 4G Decoding: Enabled
+ Advanced > Chipset Configuration > Onboard HD Audio & Onboard HDMI HD Audio: Enabled
+ Advanced > Chipset Configuration > VT-d: Disabled
+ Advanced > USB Configuration > XHCI Hand-off: Enabled
+ Advanced > CPU Configuration > C States Support: Disabled
+ Advanced > Security > Secure Boot: Disabled
+ BOOT > CSM: Enabled

### What's working
+ Sleep
+ Handoff, Sidecar, iServices
+ WiFi and Bluetooth without patching
+ Video acceleration

### Some important stuff
+ Don't copy the EFI blindly, you could harm your system
+ Use the Desktop Guide to tailor your own EFI, matching your setup
+ OpenCore logging is disabled, you should enable it for troubleshooting
+ Change the platform info when your done installing to enable iServices

### References and credits
+ [OpenCore Desktop Guide](https://dortania.github.io/OpenCore-Desktop-Guide/)
+ [csrutil](https://github.com/csrutil/DeskMini)
+ [xjn819 blog](https://blog.xjn819.com/?p=7)
