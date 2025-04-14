# rpi-auto-resize-root-partition

Complete tutorial on how to configure the Raspberry Pi image to automatically resize the
root partition to use the full unallocated space on your sd card or usb drive.

This has been tested on both ARM64 Mac and AMD64 Mac laptops.

AMD is much slower as expected due to emulation.

```sh
git clone https://github.com/jonnymacs/rpi-auto-resize-root
cd rpi-auto-resize-root
./build.sh
```

Use the Raspberry Pi Imager tool to install the img file located in custom-rpi-image/deploy
on an SD card or USB stick

[![Watch and Like the recorded video for this project on YouTube](https://img.youtube.com/vi/Q2CteZ78_ds/maxresdefault.jpg)](https://www.youtube.com/watch?v=Q2CteZ78_ds)

**[Watch and Like the recorded video for this project on YouTube](https://www.youtube.com/watch?v=Q2CteZ78_ds)** 

**[Subscribe to the channel for more similar content](https://www.youtube.com/@macmind-io?sub_confirmation=1)

Please refer to https://github.com/raspberrypi/rpi-image-gen for more information rpi-image-gen

[Follow me on X](https://x.com/jonnymacs), and don't forget to star [this GitHub repository](https://github.com/jonnymacs/rpi-tutorials)!