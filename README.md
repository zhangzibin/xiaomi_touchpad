# xiaomi_touchpad
Linux touchpad control for MI book

## Find the device name of your touchpad
Firstly, show all devices using `xinput` in command line. Then try `xinput set-prop $id "Device Enabled" 0` to disable the device named with something like touchpad. If it works, copy the device name.

## Repalce the device name
Repalce the device name in script `touchpad`.

## Setup
Put the script in a folder in `$PATH` such as `/bin/touchpad`. You may set a shortcut to control it easily.
