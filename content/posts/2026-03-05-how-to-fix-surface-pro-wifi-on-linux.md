---
title: "How to Fix Surface Pro WiFi on Linux"
date: 2026-03-05
draft: false
categories: ["linux"]
description: "How to Fix Surface Pro WiFi on Linux — guide for Linux users on Surface Pro."
---

## Introduction
As a Linux user on a Microsoft Surface Pro, you're likely no stranger to the unique challenges that come with running a non-Windows operating system on a device designed specifically for Microsoft's ecosystem. One of the most common issues faced by Surface Pro Linux users is problematic WiFi connectivity. Whether it's dropped connections, slow speeds, or an inability to connect at all, WiFi issues can be frustrating and hinder your productivity. In this post, we'll explore the common causes of Surface Pro WiFi issues on Linux and provide step-by-step solutions to get you back online.

## Understanding the WiFi Hardware on Your Surface Pro
Before we dive into troubleshooting, it's essential to understand the WiFi hardware on your Surface Pro. The Surface Pro series uses a combination of Intel and Marvell WiFi adapters, depending on the model. For example, the Surface Pro 7+ uses the Intel Wi-Fi 6 AX201 adapter, while older models might use the Marvell AVASTAR Wireless-AC Network Controller. To identify your WiFi adapter, open a terminal and run the command `lspci | grep -i wifi`. This will display information about your WiFi adapter, including the manufacturer and model.

## Troubleshooting WiFi Issues on Surface Pro Linux
Troubleshooting WiFi issues on your Surface Pro running Linux involves a combination of software and hardware checks. Here are some steps to follow:

1. **Check your WiFi adapter**: Ensure that your WiFi adapter is enabled and recognized by your Linux distribution. Run the command `ip link show` to list all network interfaces, including your WiFi adapter.
2. **Update your kernel and firmware**: Outdated kernel and firmware versions can cause WiFi issues. Run the command `sudo apt update && sudo apt full-upgrade` to update your kernel and firmware.
3. **Check your WiFi settings**: Ensure that your WiFi settings are correct, including your SSID, password, and encryption method. Run the command `nmcli connection show` to list all your network connections.
4. **Restart your WiFi adapter**: Sometimes, simply restarting your WiFi adapter can resolve connectivity issues. Run the command `sudo systemctl restart NetworkManager` to restart your WiFi adapter.

## Using External WiFi Adapters or Docks for Improved Connectivity
If you're experiencing persistent WiFi issues with your built-in adapter, consider using an external WiFi adapter or dock. These devices can provide more reliable and faster connectivity, especially in areas with weak WiFi signals. Some popular options include:

* **Anker 777 Thunderbolt 4 Dock**: This dock provides a range of ports, including Ethernet, USB-A, and USB-C, as well as a built-in WiFi adapter. [Buy on Amazon](https://www.amazon.com/dp/B0B2KBMB3M?tag=tinywhale-20)
* **CalDigit TS4 Thunderbolt 4 Dock**: This dock offers a similar range of ports to the Anker 777, including a built-in WiFi adapter. [Buy on Amazon](https://www.amazon.com/dp/B09GK8LBWS?tag=tinywhale-20)
* **Plugable 14-in-1 USB-C Dock**: This dock provides a range of ports, including Ethernet, USB-A, and USB-C, as well as a built-in WiFi adapter. [Buy on Amazon](https://www.amazon.com/dp/B08HR3MPN4?tag=tinywhale-20)

## Optimizing Your WiFi Settings for Better Performance
To optimize your WiFi settings for better performance, follow these tips:

1. **Use the 5GHz frequency band**: If your WiFi router supports the 5GHz frequency band, use it for better performance and less interference.
2. **Use WPA2 encryption**: Ensure that your WiFi network uses WPA2 encryption for better security and performance.
3. **Update your WiFi driver**: Ensure that your WiFi driver is up-to-date, as outdated drivers can cause connectivity issues.
4. **Use a WiFi analyzer tool**: Use a WiFi analyzer tool, such as `wavemon`, to analyze your WiFi signal strength and identify potential issues.

## Accessorizing Your Surface Pro for Improved Productivity
To get the most out of your Surface Pro, consider accessorizing with devices that can improve your productivity. Some popular options include:

* **Samsung T7 Shield Portable SSD**: This portable SSD provides fast and reliable storage for your files and data. [Buy on Amazon](https://www.amazon.com/dp/B09QBN6HCJ?tag=tinywhale-20)
* **Logitech MX Master 3S**: This wireless mouse provides precise and comfortable navigation, perfect for working on your Surface Pro. [Buy on Amazon](https://www.amazon.com/dp/B09HM94VDS?tag=tinywhale-20)
* **Keychron K2 Pro Mechanical Keyboard**: This mechanical keyboard provides a comfortable and precise typing experience, perfect for working on your Surface Pro. [Buy on Amazon](https://www.amazon.com/dp/B0BLP6FNGP?tag=tinywhale-20)
* **SanDisk Extreme Pro microSD**: This microSD card provides fast and reliable storage for your files and data. [Buy on Amazon](https://www.amazon.com/dp/B09X7BK27V?tag=tinywhale-20)

## Conclusion
Fixing WiFi issues on your Surface Pro running Linux requires a combination of software and hardware checks, as well as optimization of your WiFi settings. By following the steps outlined in this post, you can improve your WiFi connectivity and get the most out of your device. Consider accessorizing with devices that can improve your productivity, such as external WiFi adapters, portable SSDs, and mechanical keyboards. If you're in the market for a new Surface Pro, consider the [Microsoft Surface Pro 7+](https://www.amazon.com/dp/B08RH6WNWQ?tag=tinywhale-20), which provides a range of features and improvements over earlier models. Don't forget to pair your Surface Pro with essential accessories, such as the [Anker 65W USB-C Charger](https://www.amazon.com/dp/B09C6JNVB8?tag=tinywhale-20) and [Microsoft Surface Pro Signature Type Cover](https://www.amazon.com/dp/B07N2KFMZG?tag=tinywhale-20), to get the most out of your device.