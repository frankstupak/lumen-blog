---
title: "Install Ubuntu on Surface Pro — Step by Step 2026"
date: 2026-03-05
draft: false
categories: ["linux"]
description: "Install Ubuntu on Surface Pro — Step by Step 2026 — guide for Linux users on Surface Pro."
---

## Introduction
As a Linux user who owns a Microsoft Surface Pro, you're part of a unique group that values both the versatility of Linux and the sleek design of Microsoft's flagship tablet. Installing Ubuntu on your Surface Pro can be a great way to breathe new life into your device, especially if you're looking for a more customizable and open-source operating system. In this step-by-step guide, we'll walk you through the process of installing Ubuntu on your Surface Pro, covering everything from preparation to post-installation setup.

## Preparing Your Surface Pro for Ubuntu Installation
Before you start the installation process, it's essential to prepare your Surface Pro. This includes backing up any important files, disabling Secure Boot, and creating a bootable USB drive. To create a bootable USB drive, you'll need a USB drive with at least 8GB of free space and a tool like Rufus or Etcher. Download the latest version of Ubuntu from the official website and use Rufus or Etcher to create a bootable USB drive.

Once you've created the bootable USB drive, insert it into your Surface Pro and restart the device. As your Surface Pro boots up, press the volume down button and the power button simultaneously to enter the UEFI firmware settings. In the UEFI settings, navigate to the Boot options and set the USB drive as the first boot device. Save the changes and exit the UEFI settings.

## Installing Ubuntu on Your Surface Pro
With your Surface Pro set to boot from the USB drive, you'll be presented with the Ubuntu installation menu. Select the "Install Ubuntu" option and follow the on-screen instructions to select your language, keyboard layout, and time zone. You'll also be asked to connect to a Wi-Fi network, which is optional but recommended.

The next step is to select the installation type. You can choose to erase the entire disk and install Ubuntu, or you can choose to install Ubuntu alongside your existing operating system. If you're not planning to use your existing operating system, it's recommended to erase the entire disk and install Ubuntu.

The installation process will take around 30 minutes to an hour, depending on the speed of your Surface Pro and the USB drive. Once the installation is complete, you'll be prompted to restart your Surface Pro.

## Post-Installation Setup
After restarting your Surface Pro, you'll be presented with the Ubuntu login screen. Log in with the username and password you created during the installation process. The first thing you'll notice is that the touch screen and pen support are not working out of the box. To enable touch screen and pen support, you'll need to install the necessary drivers.

You can install the drivers by running the following command in the terminal:
```bash
sudo apt update && sudo apt install xserver-xorg-input-libinput
```
This will install the libinput driver, which provides touch screen and pen support for your Surface Pro.

## Configuring Your Surface Pro for Optimal Performance
To get the most out of your Surface Pro, you'll want to configure it for optimal performance. This includes installing the necessary drivers, configuring the power management settings, and optimizing the display settings.

One of the most important drivers you'll need to install is the SAM (Surface Aggregator Module) driver. This driver provides support for the Surface Pro's keyboard, touchpad, and other peripherals. You can install the SAM driver by running the following command in the terminal:
```bash
sudo apt install surface-control
```
This will install the surface-control package, which includes the SAM driver.

Another important driver you'll need to install is the Intel Wi-Fi driver. This driver provides support for the Surface Pro's Wi-Fi adapter. You can install the Intel Wi-Fi driver by running the following command in the terminal:
```bash
sudo apt install intel-wifi-firmware
```
This will install the intel-wifi-firmware package, which includes the necessary firmware for the Intel Wi-Fi adapter.

## Accessorizing Your Surface Pro for Linux
Now that you have Ubuntu installed on your Surface Pro, you'll want to accessorize it with the right peripherals and accessories. One of the most important accessories you'll need is a docking station. A docking station provides a convenient way to connect your Surface Pro to multiple monitors, keyboards, and other peripherals.

Some great options for docking stations include the [Anker 777 Thunderbolt 4 Dock](https://www.amazon.com/dp/B0B2KBMB3M?tag=tinywhale-20), the [CalDigit TS4 Thunderbolt 4 Dock](https://www.amazon.com/dp/B09GK8LBWS?tag=tinywhale-20), and the [Plugable 14-in-1 USB-C Dock](https://www.amazon.com/dp/B08HR3MPN4?tag=tinywhale-20). These docking stations provide a range of ports and connections, including Thunderbolt 4, USB-C, HDMI, and DisplayPort.

Another important accessory you'll need is a portable SSD. A portable SSD provides a convenient way to store and transfer large files, such as videos and photos. Some great options for portable SSDs include the [Samsung T7 Shield Portable SSD](https://www.amazon.com/dp/B09QBN6HCJ?tag=tinywhale-20). This portable SSD provides fast transfer speeds and a rugged design that can withstand rough handling.

If you're looking for a new keyboard and mouse to use with your Surface Pro, consider the [Logitech MX Master 3S](https://www.amazon.com/dp/B09HM94VDS?tag=tinywhale-20) and the [Keychron K2 Pro Mechanical Keyboard](https://www.amazon.com/dp/B0BLP6FNGP?tag=tinywhale-20). These keyboards provide a comfortable typing experience and a range of customizable features.

Finally, if you're looking for a new microSD card to use with your Surface Pro, consider the [SanDisk Extreme Pro microSD](https://www.amazon.com/dp/B09X7BK27V?tag=tinywhale-20). This microSD card provides fast transfer speeds and a large storage capacity, making it perfect for storing photos, videos, and other files.

## Conclusion
Installing Ubuntu on your Surface Pro can be a great way to breathe new life into your device. With the right drivers and accessories, you can get the most out of your Surface Pro and enjoy a seamless Linux experience. Whether you're a developer, a student, or just a Linux enthusiast, Ubuntu on the Surface Pro is a great option.

If you're looking for a new Surface Pro to use with Linux, consider the [Microsoft Surface Pro 7+](https://www.amazon.com/dp/B08RH6WNWQ?tag=tinywhale-20). This device provides a powerful Intel Core i5 processor, 16GB of RAM, and a 256GB SSD, making it perfect for running Linux.

To keep your Surface Pro charged on the go, consider the [Anker 65W USB-C Charger](https://www.amazon.com/dp/B09C6JNVB8?tag=tinywhale-20). This charger provides fast charging speeds and a compact design that's perfect for travel.

Finally, to protect your Surface Pro's screen and provide a comfortable typing experience, consider the [Microsoft Surface Pro Signature Type Cover](https://www.amazon.com/dp/B07N2KFMZG?tag=tinywhale-20). This type cover provides a comfortable typing experience and a range of customizable features, making it perfect for use with Linux.

In conclusion, installing Ubuntu on your Surface Pro is a great way to enjoy a seamless Linux experience. With the right drivers, accessories, and peripherals, you can get the most out of your device and enjoy a productive and comfortable computing experience.