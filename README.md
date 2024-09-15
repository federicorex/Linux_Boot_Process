# Linux_Boot_Process
A methodical breakdown of the Linux Boot Process

Summary of Linux Boot Process
1) BIOS/UEFI: Hardware initialization and boot device selection.
2) Bootloader (GRUB): Loads the Linux kernel into memory.
3) Kernel Initialization: Kernel starts, detects hardware, loads drivers.
4) initramfs/initrd: Temporary root filesystem with essential drivers.
5) init system (systemd): Manages the starting of system services.
6) Startup Scripts: System services are started based on run levels or unit files.
7) Login Prompt/Display Manager: User login prompt or graphical login screen.
