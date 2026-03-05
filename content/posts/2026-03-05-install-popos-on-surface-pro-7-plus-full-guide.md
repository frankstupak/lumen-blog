---
title: "Install PopOS on Surface Pro 7 Plus — Full Guide"
date: 2026-03-05
draft: false
categories: ["linux"]
description: "Install PopOS on Surface Pro 7 Plus — Full Guide — guide for Linux users on Surface Pro."
---

## Introduction
As a Linux user who owns a Microsoft Surface Pro, you're likely no stranger to the world of flexibility and customization that comes with running an open-source operating system on a versatile device. The Surface Pro 7 Plus, in particular, is a powerful machine that can handle a wide range of tasks, from basic productivity to complex development work. However, installing a Linux distribution on this device can be a daunting task, especially for those new to the Linux ecosystem. In this guide, we'll walk you through the process of installing PopOS on your Surface Pro 7 Plus, a popular and user-friendly distribution that's well-suited for this device.

PopOS is a fantastic choice for Surface Pro users, as it's designed to be highly customizable and comes with a wide range of software packages available. The distribution is based on Ubuntu, which means it has a large community of users and developers who contribute to its growth and maintenance. Additionally, PopOS has a reputation for being highly stable and secure, making it an excellent option for those who want a hassle-free Linux experience.

## Preparing Your Surface Pro 7 Plus for Installation
Before you can install PopOS on your Surface Pro 7 Plus, you'll need to prepare your device for the installation process. This involves disabling secure boot, enabling legacy boot, and creating a bootable USB drive with the PopOS installation media.

To disable secure boot and enable legacy boot on your Surface Pro 7 Plus, follow these steps:

1. Restart your device and enter the UEFI firmware settings by pressing the Volume Down button while powering on.
2. Navigate to the "Security" tab and disable "Secure Boot".
3. Save your changes and exit the UEFI firmware settings.

Next, you'll need to create a bootable USB drive with the PopOS installation media. You can do this using a tool like Rufus on Windows or the `dd` command on Linux. Make sure to download the latest version of PopOS from the official website and follow the instructions provided to create the bootable USB drive.

## Installing PopOS on Your Surface Pro 7 Plus
With your device prepared and your bootable USB drive ready, you can now begin the installation process. Insert the USB drive into your Surface Pro 7 Plus and restart the device. Enter the UEFI firmware settings again and set the USB drive as the first boot device.

Save your changes and exit the UEFI firmware settings. The PopOS installation media should now boot, and you'll be presented with a menu that allows you to try PopOS without installing it or install it directly.

Choose the "Install PopOS" option and follow the on-screen instructions to select your language, keyboard layout, and time zone. You'll also be asked to partition your device's storage, so make sure to allocate enough space for the operating system and any additional software you plan to install.

## Configuring Your PopOS Installation
Once the installation process is complete, you'll be prompted to restart your device and enter your username and password. Take this opportunity to explore the PopOS desktop environment and familiarize yourself with the various settings and options available.

One of the first things you'll want to do is configure your network settings. PopOS uses the NetworkManager service to manage your network connections, so you can use the `nmcli` command to connect to your Wi-Fi network or configure your Ethernet settings.

To connect to a Wi-Fi network using `nmcli`, run the following command:
```bash
nmcli device wifi connect <SSID> password <PASSWORD>
```
Replace `<SSID>` with the name of your Wi-Fi network and `<PASSWORD>` with your network password.

## Enhancing Your PopOS Experience with Accessories
While the Surface Pro 7 Plus is an excellent device on its own, you can enhance your overall experience with a range of accessories designed to complement its capabilities. Here are a few recommendations:

* The [Anker 777 Thunderbolt 4 Dock](https://www.amazon.com/dp/B0B2KBMB3M?tag=tinywhale-20) is an excellent choice for expanding your device's connectivity options. With multiple USB ports, an HDMI output, and a Thunderbolt 4 port, you can connect all your peripherals and accessories with ease.
* The [CalDigit TS4 Thunderbolt 4 Dock](https://www.amazon.com/dp/B09GK8LBWS?tag=tinywhale-20) is another great option for those who need a high-quality docking station. It features a compact design, multiple USB ports, and a Thunderbolt 4 port, making it perfect for connecting your device to a range of peripherals.
* For those who prefer a more portable solution, the [Plugable 14-in-1 USB-C Dock](https://www.amazon.com/dp/B08HR3MPN4?tag=tinywhale-20) is an excellent choice. It features a compact design, multiple USB ports, and an HDMI output, making it perfect for connecting your device to a range of peripherals on the go.
* If you're looking for a high-quality portable SSD to expand your device's storage, consider the [Samsung T7 Shield Portable SSD](https://www.amazon.com/dp/B09QBN6HCJ?tag=tinywhale-20). It features a rugged design, fast transfer speeds, and a large storage capacity, making it perfect for storing your files and data on the go.
* For a high-quality mouse, consider the [Logitech MX Master 3S](https://www.amazon.com/dp/B09HM94VDS?tag=tinywhale-20). It features a ergonomic design, precise tracking, and a long battery life, making it perfect for productivity and gaming.
* If you're looking for a high-quality mechanical keyboard, consider the [Keychron K2 Pro Mechanical Keyboard](https://www.amazon.com/dp/B0BLP6FNGP?tag=tinywhale-20). It features a compact design, customizable backlighting, and a range of switch options, making it perfect for typing and gaming.
* For a high-quality microSD card, consider the [SanDisk Extreme Pro microSD](https://www.amazon.com/dp/B09X7BK27V?tag=tinywhale-20). It features fast transfer speeds, a large storage capacity, and a rugged design, making it perfect for storing your files and data on the go.

## Tips and Tricks for Optimizing Your PopOS Experience
Here are a few tips and tricks to help you optimize your PopOS experience on your Surface Pro 7 Plus:

* Use the `tlp` command to optimize your device's power consumption. This can help extend your battery life and reduce heat generation.
* Use the `sysctl` command to optimize your device's network settings. This can help improve your network performance and reduce latency.
* Use the `fdisk` command to manage your device's disk partitions. This can help you allocate space for your operating system and any additional software you plan to install.
* Consider installing a third-party dock or launcher to enhance your desktop experience. Some popular options include the [Plank](https://github.com/ricotz/plank) dock and the [Albert](https://github.com/albertlauncher/albert) launcher.

## Conclusion
Installing PopOS on your Surface Pro 7 Plus can be a rewarding experience, especially for those who value flexibility and customization. With its user-friendly interface, wide range of software packages, and high level of customizability, PopOS is an excellent choice for Surface Pro users who want a hassle-free Linux experience.

By following the steps outlined in this guide, you can install PopOS on your Surface Pro 7 Plus and start enjoying the benefits of a Linux-based operating system. Remember to explore the various settings and options available in PopOS, and don't hesitate to reach out to the community for support if you encounter any issues.

Whether you're a seasoned Linux user or just starting out, PopOS is an excellent choice for your Surface Pro 7 Plus. With its robust feature set, user-friendly interface, and high level of customizability, it's the perfect operating system for anyone who wants a flexible and powerful Linux experience.

If you're looking to purchase a Surface Pro 7 Plus or any of the accessories mentioned in this guide, consider checking out the following links:

* [Microsoft Surface Pro 7+](https://www.amazon.com/dp/B08RH6WNWQ?tag=tinywhale-20)
* [Anker 65W USB-C Charger](https://www.amazon.com/dp/B09C6JNVB8?tag=tinywhale-20)
* [Microsoft Surface Pro Signature Type Cover](https://www.amazon.com/dp/B07N2KFMZG?tag=tinywhale-20)

Remember to always purchase from reputable sources and to read reviews before making a purchase. Happy shopping!