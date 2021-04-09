# Dell-Vostro-3568-macOS-Big-Sur-EFI-OpenCore-0.6.3
OpenCore EFI for Dell Vostro 3568 i5-7th gen. Everything works. Enjoy.
I have spent a lot of time in researching and setting up this EFI. Enjoy. Just put the EFI folder in EFI partition and boot it up.

## What's Working?

### Audio
**Everythings work including External Microphone!**
_(Install [ComboJack](https://github.com/hackintosh-stuff/ComboJack) for External Microphone and proper sound presets & hda verbs)_

### Bluetooth, WiFi & Ethernet
- Bluetooth works but audio stream breaks while playing something via headphones
- Use INTEL WIRELESS 3165 or any other compatible WIFI card.
  _I have used **"Intel Wireless 3165"** card._
- Realtek 8111/8168/8411 series
 
### Battery
- Works fine

### Touchpad & Keyboard
- Work smoothly, including all gestures!
- Keyboard works but I was unable to patch brightness keys if anyone can help do it.
  _(Brightness can be controlled using **Fn + s** & **Fn + b** though)_
  
### Display & Graphic Acceleration
- Working smoothly, I have done the framebuffer patching too for HDMI but haven't tested it yet

### I/O Ports 
- USB _working_
- HDMI _should work, didn't test!_
- VGA _working_
- Card Reader _not upported_
- RJ45 _working_

### Webcam
- Works fine

### iMessages & Facetime
- This is not working on my machine may be it will work on your machine
- Other iCLoud services are working just fine

**Note:** _Do not forget to generate your own PlatformInfo!_ _Follow this [OpenCore guide](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/kaby-lake.html#platforminfo) to generate PlatformInfo_
