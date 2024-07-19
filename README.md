# Install Linux on Windows with Etcher and Kubuntu 24.04 LTS

#### Overview
This repository provides a step-by-step guide on how to install Kubuntu 24.04 LTS on a Windows machine using Etcher. The guide includes downloading necessary software, creating a bootable USB drive, and installing Kubuntu.

#### Table of Contents
1. [Prerequisites](#prerequisites)
2. [Downloading Etcher](#downloading-etcher)
3. [Downloading Kubuntu 24.04 LTS](#downloading-kubuntu-2404-lts)
4. [Creating a Bootable USB Drive](#creating-a-bootable-usb-drive)
5. [Installing Kubuntu](#installing-kubuntu)
6. [Post-Installation Steps](#post-installation-steps)
7. [Troubleshooting](#troubleshooting)

#### Prerequisites
- A Windows PC
- A USB drive (at least 8GB)
- Internet connection

#### Downloading Etcher
1. Visit the [Etcher download page](https://etcher.balena.io/#download-etcher).
2. Download the appropriate version for Windows.
3. Install Etcher on your Windows machine.

#### Downloading Kubuntu 24.04 LTS
1. Visit the [official Kubuntu download page](https://kubuntu.org/getkubuntu/).
2. Download the Kubuntu 24.04 LTS ISO file.

#### Creating a Bootable USB Drive
1. Insert your USB drive into your Windows PC.
2. Open Etcher.
3. Select the Kubuntu 24.04 LTS ISO file you downloaded.
4. Select the USB drive you inserted.
5. Click "Flash!" to create the bootable USB drive.

#### Installing Kubuntu
1. Reboot your Windows PC and enter the BIOS/UEFI settings (usually by pressing F2, F12, Delete, or Esc during startup).
2. Change the boot order to prioritize booting from the USB drive.
3. Save and exit the BIOS/UEFI settings.
4. Your PC will now boot from the USB drive, and the Kubuntu installer will start.
5. Follow the on-screen instructions to install Kubuntu. Select your preferred language, keyboard layout, and installation type (e.g., alongside Windows or replacing it).
6. Create a user account and set up a password.
7. Complete the installation and reboot your PC.

#### Post-Installation Steps
1. Remove the USB drive and reboot into Kubuntu.
2. Update your system by opening a terminal and running:
   ```bash
   sudo apt update
   sudo apt upgrade
   ```
3. Install additional software and drivers as needed.

#### Troubleshooting
- **Boot Issues**: If your PC doesn't boot from the USB drive, ensure the BIOS/UEFI settings are correctly configured.
- **Installation Errors**: Check the integrity of your ISO file and the USB drive.
- **Driver Issues**: Install necessary drivers from the Kubuntu repository.

#### Contributing
Feel free to submit issues or pull requests if you encounter any problems or have suggestions for improving this guide.

#### License
This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

This README provides a clear, step-by-step guide for installing Kubuntu 24.04 LTS on a Windows machine using Etcher, ensuring a smooth transition for users looking to switch to or dual-boot with Linux.
