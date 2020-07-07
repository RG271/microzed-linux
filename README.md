# microzed-linux
SD card Linux image for MicroZed
================================

This is an attempt to create an SD card Linux image for the MicroZed board.
The boot partition files were created using buildroot-2020.02.3 (https://buildroot.org).
Buildroot creates a RAM-disk based SD card image. The bootargs in the device tree file
were modified; so, it should look for a rootfs in the SD card's second partition.
A very nice rootfs is provided by PYNQ (http://www.pynq.io).
