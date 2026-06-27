# 💾 Installation

> Learn how to install Ventoy on your USB drive and understand the most important installation options.

---

# 📝 Overview

Installing Ventoy is a quick and straightforward process. Unlike traditional bootable USB tools, Ventoy only needs to be installed **once** on a USB drive.

After the installation is complete, you can simply copy ISO files onto the USB drive like any other file. There is no need to recreate or reformat the drive every time you want to install a different operating system.

> **Warning:** Installing Ventoy will erase all existing data on the selected USB drive.

---

# 📋 Before You Begin

Before installing Ventoy, make sure you have:

* ✅ Downloaded and extracted the latest Ventoy release
* ✅ A USB flash drive connected to your computer
* ✅ Backed up any important files from the USB drive
* ✅ Administrator privileges on your system

---

# 🚀 Installing Ventoy

1. Open the extracted Ventoy folder.
2. Run **Ventoy2Disk.exe** as Administrator.
3. Select your USB drive from the list.
4. Double-check that you've selected the correct device.
5. Click **Install**.
6. Confirm the warning messages.
7. Wait for the installation to complete.

Once finished, Windows will detect the USB drive again.

Your USB drive is now ready to use with Ventoy.

---

# 📂 Using Your Ventoy USB

After installation, open your USB drive in File Explorer.

You'll notice it behaves like a normal storage device.

Simply copy any supported ISO files onto the drive.

For example:

```text
Fedora.iso
Debian.iso
Arch.iso
```

Safely eject the USB drive when you're finished copying files.

---

# 💾 GPT vs MBR

During installation, Ventoy allows you to choose between **GPT** and **MBR** partition styles.

### GPT (Recommended)

GPT (GUID Partition Table) is the modern partitioning standard.

Advantages:

* Supports UEFI systems
* Supports Secure Boot
* Better compatibility with modern hardware
* Recommended for almost all computers manufactured in the last decade

### MBR

MBR (Master Boot Record) is the older partitioning format.

Advantages:

* Better compatibility with older BIOS-based computers
* Useful for legacy hardware

Limitations:

* Less flexible than GPT
* Designed for older systems
* Not recommended unless compatibility requires it

> **Recommendation:** Use **GPT** unless you're specifically installing operating systems on older BIOS-only computers.

---

# 🔐 Secure Boot

Most modern computers use **UEFI Secure Boot**.

Ventoy supports Secure Boot, but the first time you boot from the USB drive, you may be asked to enroll Ventoy's Secure Boot key.

This is completely normal.

Simply follow the on-screen instructions to enroll the key once. After that, Ventoy will boot normally on future startups.

If your computer uses Legacy BIOS instead of UEFI, Secure Boot does not apply.

---

# ✅ Installation Complete

Congratulations!

Your Ventoy USB drive is now ready.

From this point onward, installing a new operating system is as simple as:

1. Downloading an ISO file.
2. Copying it to the USB drive.
3. Booting from the USB.
4. Selecting the desired ISO from the Ventoy menu.

No reinstallation of Ventoy is required.

---

# 💡 Tips

* Keep Ventoy updated from time to time.
* Use descriptive filenames for your ISO files.
* Organize ISOs into folders if you store many of them.
* Always eject the USB safely before unplugging it.

---

# 👋 Final Notes

One of Ventoy's greatest strengths is its simplicity. Once installed, your USB drive becomes a reusable multi-boot device capable of storing multiple operating systems at the same time.

The next guide covers how to customize Ventoy, including Secure Boot settings, themes, plugins, and other useful configuration options.