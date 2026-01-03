# Arch Linux Tips and Notes
This is my general purpose guide to things I've learned from being on Arch for a little over a year. 
Not all encompassing, but mainly helpful for me and hopefully others as a reference.

## Install
Install is pretty easy, and there is a guided script now that I rec for anyone new to linux entirely, unless you want to get ganular with a manual install

### Ventoy
Ventoy is a very handy tool for making a bootable USB that can contain multiple .iso files
[Install Instructions](https://www.ventoy.net/en/doc_start.html)
[Arch Image Download](https://archlinux.org/download/)

I reccomend grabbing a USB and setting it so you can boot Arch, or any other .iso realy

### Arch Install

Arch can be installed manually step by step, but also has a script to install via a guided menu: [archinstall](https://wiki.archlinux.org/title/Archinstall)
I highly reccomend this honestly, it's gotten a lot better since I used it a year or so ago. However you can still follow the manual guide [here](https://wiki.archlinux.org/title/Installation_guide)

Majority of the options are very self explanitory, go through one by one and lookup anything you might not be sure about.

Very important, make sure you enable networking, this can easily be missed and will of course cause issues should you need networking.

### Nvidia
Current gen Nvidia cards should work roughly out of the box now. For detailed ref, please see the [Nvidia Page](https://wiki.archlinux.org/title/NVIDIA)
modeset is needed for Wayland support and on a fresh install _should_ be enabled by default.

Note that for fan controls, there are still issues (as of 2026) with some built in controls. Please see this page on fan controls in arch: [Fan Controls](https://wiki.archlinux.org/title/Fan_speed_control)

From my experience, I really like [CoolerControl](https://aur.archlinux.org/packages/CoolerControl). It's pretty verbose but allows for a nice GUI and a lot of customizability. Do note, there seems to be a speed minimum on Nvidia cards such that you cannot run them under 40% speed.

## FSTAB
This is the file that mounts your drives, local and network. You shouldn't need to edit after install, but there are exceptions.

### Network Drives


### Network Drives

## Terminal

## DE/WM

## Pacman

## AUR

## General Apps

## Gaming

## Helpful Commands

