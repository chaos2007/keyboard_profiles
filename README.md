# keyboard_profiles
just a place to put my keyboard configs

## Install udev rules
```
sudo cp 99-keyboard.rules /etc/udev/rules.d/
sudo udevadm control --reload-rules
sudo udevadm trigger
```

## How to run the Image, this will bypass adding vias devrules.
```
DISABLE_SUDO_PROMPT=1 ~/via-2.0.5-linux.AppImage
```
