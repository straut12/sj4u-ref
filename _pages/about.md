---
permalink: /about/
title: "About"
toc: true
toc_sticky: true
---

# Header content

## sub header

## another sub header

# H1 this is header 1

<h2>General Stuff</h2>

Instructions for different display (/boot/config.txt) or can change to boot
to 'cli' and run headless with virtual VNC.

Quick summary to help decide which device is best and help when downloading packages.  
All devices below have built in wi-fi.

|model|core       |cpu           |ARM  |arm  |Hz    |RAM    |Power Usage*  
|-----|-----------|--------------|:----|:---:|------|-------|------------  
|pi0w |single core|Broadcom2835  |ARM11|armv6|1GHz  |512MB  |0.7/1.2 Watts  
|pi3A+|quad core  |Broadcom2837B0|A53  |armv7|1.4GHz|512MB  |1.2/2.3 Watts  
|pi3B |quad core  |Broadcom2837  |A53  |armv7|1.2GHz|1GB    |1.3/2.5 Watts  
|pi3B+|quad core  |Broadcom2837B0|A53  |armv7|1.4GHz|1GB    |1.7/3.0 Watts  
|pi4  |quad core  |Broadcom2711  |A72  |armv8|1.5GHz|2,4,8GB|3.5/5.0 Watts  

* Low side is idle and high side is using programs.  Numbers are estimated.  
When working on a solar or battery project need to measure the power usage for that  
specific pi setup.  Watts (Power) = I (currrent A) x V (voltage)

Notes for RPi4
- has dual display ports (having 2 screens is nice for working on projects)
- requires larger power supply and type-C charging cord.

# this is header 2

<h2>Network</h2>

Some network commands

	route -n
	ifconfig