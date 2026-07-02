Home / 01 - Ventoy

# 💾 Installation

> *"Install once, use forever — simply copy new ISO files whenever you need them."*

---

# 📝 About

Installing Ventoy is quick and straightforward. Unlike traditional bootable USB tools, Ventoy only needs to be installed **once** on a USB drive.

After the installation is complete, you can simply copy ISO files onto the drive like any other file. There is no need to recreate or reformat the USB drive every time you want to install a different operating system.

> ⚠️ **Warning:** Installing Ventoy will erase **all existing data** on the selected USB drive.

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
3. Select your USB drive from the device list.
4. Double-check that the correct USB drive is selected.
5. Click **Install**.
6. Confirm the warning messages.
7. Wait for the installation to finish.

Once the process is complete, Windows will automatically detect the USB drive again.

Your Ventoy USB drive is now ready to use.

---

# 📂 Using Your Ventoy Drive

After installation, open the USB drive in File Explorer.

It behaves like a normal storage device, allowing you to copy, move, or delete supported ISO files whenever needed.

For example:

```text
Fedora.iso
Debian.iso
Arch.iso
```

When you're finished copying files, safely eject the USB drive before unplugging it.

---

# 💽 GPT vs MBR

During installation, Ventoy allows you to choose between **GPT** and **MBR** partition styles.

### ✅ GPT (Recommended)

GPT (**GUID Partition Table**) is the modern partitioning standard used by most computers today.

Advantages:

* Supports UEFI firmware
* Compatible with Secure Boot
* Better support for modern hardware
* Recommended for almost every computer manufactured within the last decade

### 🖥️ MBR

MBR (**Master Boot Record**) is the older partitioning standard.

Advantages:

* Better compatibility with legacy BIOS systems
* Useful for older computers

Limitations:

* Less flexible than GPT
* Designed for legacy hardware
* Not recommended unless compatibility requires it

> 💡 **Recommendation:** Choose **GPT** unless you're specifically working with an older computer that only supports Legacy BIOS.

---

# 🔐 Secure Boot

Most modern computers use **UEFI Secure Boot**.

Ventoy fully supports Secure Boot. The first time you boot from your Ventoy USB drive, you may be asked to enroll Ventoy's Secure Boot key.

This is expected behavior and only needs to be completed once.

After enrolling the key, Ventoy will boot normally on future startups.

If your computer uses Legacy BIOS instead of UEFI, Secure Boot does not apply.

---

# ✅ Installation Complete

Congratulations!

Your Ventoy USB drive is now ready.

From now on, installing another operating system is as simple as:

1. Download an ISO file.
2. Copy it to your Ventoy USB drive.
3. Boot from the USB drive.
4. Select the desired ISO from the Ventoy boot menu.

No additional installation or formatting is required.

---

# 💡 Tips

* Keep Ventoy updated to benefit from new features and compatibility improvements.
* Use descriptive filenames for your ISO images.
* Organize your ISO files into folders if you maintain a large collection.
* Always safely eject the USB drive before disconnecting it.

---

# 👋 Final Notes

One of Ventoy's greatest strengths is its simplicity. Once installed, your USB drive becomes a reusable multi-boot device capable of storing multiple operating systems at the same time.

The next section explains how to customize Ventoy with themes, plugins, Secure Boot options, persistent storage, and other useful configuration features.

---

# ➡️ Next Step

➡️ **Continue reading:** [Configuration](Configuration/README.md)