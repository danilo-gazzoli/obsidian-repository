To use [[Bluetooth]] on [[Linux]] you need tom make sure that the bluetooth driver and management software is installed. 

# 1. Bluez

The linux bluetooth is powered by `bluez` (oficial implementation of bluetooth protocol to Linux). This package is necessary to the system can interact and detect Bluetooth devices.

To install bluez try: `yay -S bluez` or `sudo pacman -S bluez`.

# 2. Bluez-utils

The `bluez-utils` is a devtools package, which provides commands to interect with bluetooth. The `bluetoothctl` is a program include in this devtools.

To install `bluez-utils` try: `yay -S bluez-utils` or `sudo pacman -S bluez-utils`.

# 3. Turn on and init bluetooth services

After install `bluez`, it's necessary turn on bluetooth services so that is starts automatically with the system with the following commands:

```
sudo systemctl enable bluetooth
sudo systemctl start bluetooth
```

These commands will ensure that the bluetooth services is started during boot and will also start the service immediately.