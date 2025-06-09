# Linux Boot Process

This repository contains an explanation of the **Linux boot process**, which describes how a Linux system starts from powering on the machine to reaching the login screen.

## 🔄 Boot Process Flow:

BIOS/UEFI → MBR/GPT → GRUB → Kernel → initramfs → systemd → Target → Login

## 📌 Components Explained

- **BIOS/UEFI**: Initializes hardware and hands off to the bootloader
- **MBR/GPT**: Disk partitioning systems
- **GRUB**: Bootloader that loads the Linux kernel
- **Kernel**: Core of the OS; manages hardware
- **initramfs**: Temporary root filesystem for kernel initialization
- **systemd**: Init system to start services and targets
- **Target**: A defined group of services (like `graphical.target`)
- **Login**: User login prompt or graphical login screen
