---
title: InstallFest 2026 Get started with Linux
---
Welcome to InstallFest! We're glad you're here. This guide will walk you through the basics of Linux and how to get the most out of the USB drive you received from the UMBC Linux Users Group (LUG).

{{< callout type="info" >}}
  **Which drive do I have?** The drives handed out at InstallFest 2026 include **Tails**, **Linux Mint (Cinnamon)**, **Debian Live (XFCE)**, **Fedora KDE**, and **CachyOS**. If you received an older drive, the lineup may differ, for example, **Debian Net Install** instead of Debian Live, and no CachyOS. Everything in this guide still applies; just match the systems below to what you see in your drive's Ventoy menu.
{{< /callout >}}

## Disclaimer

The UMBC Linux Users Group (LUG) and all affiliated individuals and organizations, including the University of Maryland, Baltimore County (UMBC), will not be held liable for any damage to hardware or loss of data that may occur on your system. Participants acknowledge that installing Linux carries a small, inherent risk, and by proceeding, you are accepting full responsibility for your own system. We strongly recommend that you back up all important files before the installfest.

## What Is Linux?

**Linux** is a free and open-source operating system. It's known for being secure, highly customizable, and is used everywhere; from personal computers and web servers to supercomputers.

### Why Choose Linux?

* **Privacy:** Protect your data and stay anonymous online. Try **Tails** for secure, no-trace browsing.
* **Revive Old Hardware:** Linux runs efficiently on older computers that struggle with newer versions of Windows.
* **Stay Supported:** Windows 10 reached its end of life on October 14, 2025, and many machines can't officially run Windows 11. Linux keeps those computers secure, current, and out of the landfill.
* **Play Games:** Thanks to tools like Proton and Steam, thousands of Windows games run on Linux - come check out our **LAN Night**
* **Flexibility:** Customize everything, from the look and feel to the software and the entire desktop environment.


## Your USB Drive: Powered by Ventoy

Your USB drive is loaded with **Ventoy**, a tool that lets you choose which operating system to boot into. Think of it as a multi-OS drive: start the computer, pick a distro from the menu, and you're in.

Here's what's on the 2026 drives:

| Distribution | What it is | Great for |
| --- | --- | --- |
| **Tails** | A privacy-focused live system that routes your traffic through the Tor network and leaves no trace on the host machine. | Anonymous browsing |
| **Linux Mint (Cinnamon)** | A beginner-friendly desktop with a familiar, Windows-like layout and a large, well-documented community. | First-time Linux users |
| **Debian Live (XFCE)** | Rock-solid and famously stable, with a lightweight XFCE desktop that stays fast on older hardware. A good starting point for advanced users who want full control. | Minimal, dependable setups |
| **Fedora KDE** | A modern, polished KDE Plasma desktop with recent software from the Fedora project. | A sleek, up-to-date desktop |
| **CachyOS** | An Arch-based distro tuned for performance, with a custom kernel and CPU-optimized packages. New software arrives fast. | Gaming and power users |

All of these run as **live** systems, so you can try them out without installing anything.

### Want to Try Another Linux Distro?

You can add other Linux "distros" (versions) to your drive.

1.  Find a distro you like on [DistroWatch](https://distrowatch.com/dwres.php?resource=popularity) and download its ISO file.
2.  Insert the USB drive into your computer.
3.  Open the USB drive and find the partition that contains the ISO files. If the drive shows two partitions, it's the large one.
4.  The drive is usually close to full, so you'll likely need to delete an existing ISO to make room. The full desktop distros (Mint, Fedora, and CachyOS) tend to be the largest.
5.  Copy your new ISO file to the same location.

## How to Boot from the USB Drive

1.  **Insert** the USB drive.
2.  **Restart** your computer.
3.  As your computer starts, press the **boot menu** key (often `F12`, `Esc`, or `Del`).
4.  Select your USB drive from the menu.
5.  Choose a system from the Ventoy menu to try it out.

***Tip:*** If you have trouble, you may need to disable **Secure Boot** in your computer's BIOS/UEFI settings.


## Ways to Try Linux Without Installing It

You don't have to install Linux to use it. Here are a few ways to get started:

* **Live USB:** Boot from the USB drive to try Linux temporarily without making any changes to your computer's hard drive.
* **Virtual Machine:** Run Linux as a program inside Windows or macOS using software like VirtualBox.
* **Windows Subsystem for Linux (WSL):** A tool for Windows 10/11 that lets you use Linux command-line tools without replacing your operating system.


## Installing Linux Permanently

If you love what you see, you can install Linux on your computer.

{{< callout type="warning" >}}
  **This will erase your current system!**
  Be sure to back up all your important files before you proceed.
{{< /callout >}}

### Backup Recommendations

* **External hard drive or USB stick**
* **Cloud storage** (Google Drive, Dropbox, etc.)
* **Another computer**

### Dual-Booting (Advanced)

If you want to install Linux alongside your existing Windows system, you can set up a **dual-boot**. This is a more advanced process, but it allows you to choose between Windows and Linux every time you start your computer.

{{< callout type="warning" >}}
  **Risk of Data Loss.**
  Dual-booting requires you to resize existing partitions. While uncommon, this always carries a risk of data loss. Back up your data first!
{{< /callout >}}

The **Linux Mint** installer makes this process straightforward:

1.  Boot to the Linux Mint system on your USB drive.
2.  During the installation, when you reach the "Installation Type" screen, select **`Install Linux Mint alongside Windows Boot Manager`**.
3.  You can then use the slider to choose how much space to allocate to each operating system. Make sure to leave enough room for both to grow.
4.  Once the installation is complete, you'll see a menu (called GRUB) every time you start your computer, giving you the option to boot into either Linux Mint or Windows.

*Note: While other distros can be dual-booted, the process may not be as intuitive. Don't hesitate to find a guide or ask for help!*


## Recommended Guides

* [**Linux Mint** Installation Guide](https://linuxmint-installation-guide.readthedocs.io/)
* [**Fedora** Install Guide](https://docs.fedoraproject.org/en-US/quick-docs/creating-and-using-a-live-installation-image/)
* [**Debian** Installation Guide](https://www.debian.org/releases/stable/amd64/)
* [**Tails** Install Guide](https://tails.net/install/linux/index.en.html)
* [**CachyOS** Wiki & Installation Guide](https://wiki.cachyos.org/)
* [**Ventoy** User Guide](https://www.ventoy.net/en/doc_start.html)


## Need Help?

Join the **UMBC Linux Users Group (LUG)**!

* **Weekly Meetings:** Wednesdays at 7:15 PM
* **Join our Discord:** [https://sh.lug.umbc.edu/discord](https://sh.lug.umbc.edu/discord)
* 