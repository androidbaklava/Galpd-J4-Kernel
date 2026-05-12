# Galpd-J4 Kernel

Custom kernel for Samsung Galaxy J4+ / j4primelte / MSM8917 on Android 10 LineageOS-based ROMs.

## Galpd-J4 v3.3 Features

- CPU overclock up to 1651 MHz
- GPU overclock up to 672 MHz
- Screen refresh target: 63 Hz
- CPU input boost: 1651 MHz / 100 ms
- Default I/O scheduler: deadline
- KSM support enabled, not forced
- zRAM support enabled, not forced
- NTFS read-only support
- TCP Westwood default
- Extra TCP congestion algorithms: BIC, CUBIC, HTCP, HYBLA, VEGAS, SCALABLE, LP, VENO, YEAH, ILLINOIS
- Default CPU governor remains performance

## Flashing

Flash to Boot partition only.

If you want root:
1. Patch the boot image in Magisk.
2. Reboot to TWRP.
3. Install Image.
4. Select the Magisk-patched image.
5. Flash to Boot.

For other ROMs, repack using that ROM's own boot.img ramdisk. Do not reuse a LineageOS ramdisk on another ROM.

## Warning

 * I'm not responsible for bricked devices.
 * Please do some research if you have any concerns about features included in the products you find here before flashing it! 
 * YOU are choosing to make these modifications, and if you point the finger at me for messing up your device, I will laugh at you. 
 * Your warranty will be void if you tamper with any part of your device / software.
 *Flash at your own risk. Keep a working boot image ready so you can restore from TWRP if needed.
