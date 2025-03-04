# Welcome to KéOS
## What is KéOS?
~~KéOS is an alternative, open-source web OS that brings bright new features. It includes high levels of customization and easy-to-use tools for developers. The best part? KéOS is designed to be used *in conjunction* with Windows 96. It is *not* designed to be a replacement for it. There's a version of KéOS that can easily be booted on top of the Windows 96 website. We also have the KéOS Bootloader - a small minikernel for Windows 96 that lets you choose whether to boot from Windows 96 or another kernel you have installed. KéOS can also mount your Windows 96 partition - allowing you to fix problems that might not be able to be fixed from the Windows 96 recovery environment.~~
edit: i cant decide whether it should be a web os, or a real os, or both

## Why does it exist?
In computer applications, we had to make a spreadsheet and powerpoint about our made-up company. That's boring... unless it was a real company! So, uh, yeah... that's why this started.

## How to Install
Just download the KéOS Bootloader Tool for Windows 96. It'll install KéOS Bootloader. It'll also ask you if you want to install KéOS as well. The next time you open windows96.net, you'll be prompted on which OS you want to boot in.

## ~~F~~*N*AQ
### Can KéOS run Windows 96 apps?
No. KéOS can not run Windows 96 apps, and Windows 96 can not run KéOS apps. KéOS has a completely different API structure - including built-in sandboxing and lots of API wrappers; where as Windows 96 has a priority of allowing apps to run as freely as possible to benefit the user. However, some apps that ship with KéOS also have a version for Windows 96, and it is possible to use KéOS as a development environment for Windows 96 (including the process of testing apps).

### Can you boot Windows 96 and KéOS at the same time?
While you can't boot two of your partitions at the same time, you *can* however, create a VM. We plan to develop an app in the future, called KéVM, which allows you to run web OSes in a VM. It will be available for KéOS, Windows 96 (v2sp2 and newer), and possibly receive an Electron app release.
