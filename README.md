# linux-tree-v0.000002
Custom Linux earlier. 

# How to run?

Packages need: spice-client-gtk, qemu-system-x86_64

Command to run: qemu-system-x86_64 -kernel bzImage -initrd rootfs.img -m 2G -append "rdinit=/init" -device intel-hda -device hda-duplex,audiodev=spice -audiodev spice,id=spice -spice port=5930,disable-ticketing=on.

Open another terminal and enter: spicy --host=127.0.0.1 --port=5930

# Thank to download! :) 
# Good luck ! :)
