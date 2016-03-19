# Multiboot USB
USB drive GRUB configurations that support booting off of a number of
a number of different types of ISO images.

## Installing
1. `grub-install --removable --recheck --boot-directory=<PATH TO MOUNT>/boot /dev/sdX`
2. Copy these config files to `boot/grub`
