---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Setting up Open-sourced Circuit Design (OCD) tools"
subtitle: ""
summary: "Steps for setting up Opensource Circuit Design tools on Linux using WSL "
authors: [admin]
tags: [tools, cad, pdk, sky130, wsl, linux, opensource]
categories: []
date: 2022-03-11T19:15:44+08:00
lastmod: 2022-03-11T19:15:44+08:00
featured: false
draft: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [opensource]
---
If you use Windows OS at home and want to start designing circuits using Open Circuit Design (OCD) tools and Open PDKs, you have to install Windows Subsystem for 
Linux (WSL). You could also download and use VMware to run Linux on Windows. WSL seems faster.

I will use the SkyWater130 PDK. Most of the information here, I gathered from Tim's [SKY130 installation instructions](http://opencircuitdesign.com/open_pdks/install.html) at [Opencircuitdesign.com](http://opencircuitdesign.com). I am not an IC CAD or software expert and I had to spend some time to search for information to fill in the gaps for some of the steps in the installation process. I will *try my best* to document all of them here and point you to other resources I went through.

## 1. Installing WSL2, Ubuntu and X Server
I am running Windows 10 Pro (Version 21H1, OS Build 19043.1586). Before I could run Ubuntu, I had to setup WSL2 on Windows. The full installation steps can be found [here](https://medium.com/@japheth.yates/the-complete-wsl2-gui-setup-2582828f4577).  The link takes you through the install of 

1. WSL2
2. Ubuntu
3. Desktop manager (GUI)
4. Xserver

When it came to the GUI, I experienced issues with `xubuntu-desktop` (window icons don't appear and mouse cursor lags), so I suggest that you install `ubuntu-mate-desktop` instead when you reach that step.

This part of the install went relatively smoothly for me ????

> Windows 11 comes with [native GUI support](https://docs.microsoft.com/en-us/windows/wsl/tutorials/gui-apps), so if you have Win 11, you can probably do without Xserver.

## 2. Installing Ngspice


## 3. Installing SKY130

## Other resources