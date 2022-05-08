# USB Bluetooth 5.0 Linux Driver
Linux Drivers for Generic Bluetooth 5.0 USB Adapters

To install it:

1. Open a terminal and paste the following commands:
```
git clone https://github.com/Mutcholoko/Bluetooth5LinuxDriver.git

cd Bluetooth5LinuxDriver

sudo cp rtl8761b_config /usr/lib/firmware/rtl_bt/rtl8761b_config.bin

sudo cp rtl8761b_fw /usr/lib/firmware/rtl_bt/rtl8761b_fw.bin
```

2. Unplug and replug the adapter or reboot your computer.
3. Enjoy!


This is based on [an article on Medium](https://medium.com/nerd-for-tech/how-to-install-unsupported-bluetooth-5-0-dongle-on-linux-4bf34aa99fed) by Filipe Pires. I only created this repo to keep control and have a safe spot to keep the files as I need them recurrently. These are all open source files.

You will need to repeat this process everytime you update your kernel.
