# Squeezelite-Controller

pulseaudio-module-bluetooth has many dependecies!

But it must be installed for bluetooth audio devices

```
sudo apt install snips-injection bluealsa pulseaudio-module-bluetooth
sudo adduser pi bluetooth
sudo reboot
```

```bash
sudo apt install squeezelite
sudo systemctl disable squeezelite
sudo systemctl stop squeezelite
```