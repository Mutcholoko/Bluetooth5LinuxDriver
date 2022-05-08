# USB Bluetooth 5.0 Linux Driver
Linux Drivers for Generic Bluetooth 5.0 USB Adapters

To install it:
1. Simply download the project as a .zip.
2. Unpack the .zip in any directory.
3. Open a terminal on the directory you have unzipped the file and type...

```
sudo cp rtl8761b_config /usr/lib/firmware/rtl_bt/rtl8761b_config.bin

sudo cp rtl8761b_fw /usr/lib/firmware/rtl_bt/rtl8761b_fw.bin
```
4. Unplug and replug the adapter or reboot your computer.
5. Enjoy!


This is based on [an article on Medium](https://medium.com/nerd-for-tech/how-to-install-unsupported-bluetooth-5-0-dongle-on-linux-4bf34aa99fed) by Filipe Pires. I only created this repo to keep control and have a safe spot to keep the files as I need them recurrently. These are all open source files.

You will need to repeat this process everytime you update your kernel.
