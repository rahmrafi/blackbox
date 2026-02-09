# blackbox the GRUB theme
Simplistic and minimalist, the GRUB theme design gives an understated impression and a clean look, focusing solely on functionality and efficiency. This type of design is also trending nowadays.

![preview](/preview/blackbox.png)

## Caution ⚠️
> **Before installing this theme, make sure you understand what you are doing. If GRUB configuration is not done carefully, it will have a negative impact on your system.**

## How to install
1. Clone this repository
```
git clone https://github.com/rahmrafi/blackbox.git
```
2. Copy theme to boot theme location
```
sudo cp -r blackbox /boot/grub/theme/
```
3. Edit GRUB configuration
```
sudo nano /etc/default/grub
```
4. Important parts
```
GRUB_THEME="/boot/grub/themes/blackbox/theme.txt"

GRUB_GFXMODE=auto

#GRUB_TERMINAL_OUTPUT=console
```
> Set GRUB_THEME to theme location, GRUB_GFXMODE can be set to auto or 1920x1080, and make sure GRUB_TERMINAL_OUTPUT is commented out.

5. Reboot your system

## Notes 📝
> **This theme is intended for desktop screens with a resolution of 1920x1080 pixels, if the display is less precise than this, it needs to be adjusted in theme.txt. Change left and top on each label and boot_menu to match your screen resolution.**
