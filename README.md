# Dell-Vostro-3568-macOS-EFI-OpenCore
OpenCore EFI for Dell Vostro 3568 i5-7th gen. Everything works. Enjoy.
I have spent a lot of time in researching and setting up this EFI. Enjoy. Just put the EFI folder in EFI partition and boot it up.

## What's Working?

### Audio
**Everythings work including External Microphone! Use layout-id 13 alongwith combojack and remove ssdt-alc256.aml file from acpi**
_(Install [ComboJack](https://github.com/hackintosh-stuff/ComboJack) for External Microphone and proper sound presets & hda verbs)_

### Bluetooth, WiFi & Ethernet
- Bluetooth works including streating audio, battery indicator and auto connect.
- Use INTEL WIRELESS 3165 or any other compatible WIFI card.
  _I have used **"Intel Wireless 3165"** card._
- Realtek 8111/8168/8411 series
 
### Battery
- Works fine after Power Management using CPUFriendFriend 

### Touchpad & Keyboard
- Work smoothly, including all gestures!
- Keyboard works including brightness keys
  _(Brightness can be controlled using **Fn + s** & **Fn + b** too)_
  
### Display & Graphic Acceleration
- Working smoothly (HDMI audio & Video works)

### I/O Ports 
- USB _working_
- HDMI _working_
- VGA _working_
- RJ45 _working_
- Headphone Jack _working_
- Card Reader _not upported_

### Webcam
- Works fine

### Fingerprint
- Why would you event think that? It will not work... :( 

### iMessages & Facetime
- Working fine (you may not get it working at first you need to set platform info values properly and reset the NVRAM)
- Other iCLoud services are working just fine

**Note:** _Do not forget to generate your own PlatformInfo!_ _Follow this [OpenCore guide](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/kaby-lake.html#platforminfo) to generate PlatformInfo_
