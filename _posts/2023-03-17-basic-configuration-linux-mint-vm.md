---
title: "Checking basic configuration in a Linux Mint Virtual Machine"
# date: 2023-03-17T15:34:30-04:00
categories:
  - blog
tags:
  - Linux
  - Linux Mint
  - Virtual Machine
---

An Operating system (OS) serves as a bridge between a computer's user and its hardware. Instead of applications (like browser) interacting with the computer hardware directly, they can use the OS as abstraction layer between the two. 

As most servers use Linux OS, developers need to make themselves comfortable with Linux and its command line interface (CLI). It can be easily done by using a hypervisor such as VirtualBox, a software that allows you to build a virtual machine (VM) with any OS on your own personal computer. This VM will have dedicated amounts of CPU, memory, and storage that are "borrowed" from the physical host computer.

Lets take a Linux Mint Virtual Machine, for example and check some basics configuration using its CLI:

You can follow [these steps][installation] to create a Linux Mint VM or if you have any issues creating the VM locally, you can use [this free online VM platform][online-vm] to get access to Linux Mint.
{: .notice--info}

1. Check which package manager it uses (yum, apt, apt-get)
2. Which CLI editor is configured (Nano, Vi, Vim)
3. What software center/software manager it uses
4. Which shell is configured for our user




[installation]: https://linuxmint-installation-guide.readthedocs.io/en/latest/
[online-vm]: https://www.onworks.net/component/content/article?id=65735:free-linux-mint-online

