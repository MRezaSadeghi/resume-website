---
title: Laboratory Reactor
summary: A measurement device for controlling rotation speed of a laboratory reactor and monitor its torque in real time for Ava Polymer Company.

tags:
- industrial
date: "2020-07-03"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:

- icon: battle-net
  icon_pack: fab
  name: Ava polymer
  url: http://avapolymer.ir/

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---

# TMSC Reactor System
A significant number of chemical reactions, besides a reactor, require a measurement system to allow the technicians to be aware of reaction parameters. TMSC Reactor is a device to do both stirring and monitoring. This device is able to stir the batch with various shafts and impellers at the desired speed and also it is able to monitor an index of the implied torque from the composition inside the batch. Various parts of this device will discuss in the following sections.  It is worth mentioning that similar industrial assets (without the software) cost more than 1100$ and our device is a low-budget solution for about half of the conventional assets price.

<p align="center"><a><img src="https://www.lambertmech.ir/project/pmdc/TMSC-P21.jpg" alt="TMSC P21" height="300" ></a></p>

## Properties
- Speed: 30-500 rpm
- Torque: up to 4.2 kg-cm
- Shaft diameter: 5-10 mm
- Shaft length: up to 50cm
- Input voltage: 220 v
- Maximum power: 180W

## Main Parts
The main parts of TMSC include the shaft and impeller, motor, power & driver box, and the TMCS software.

### Shaft system and Speed control
The provided chunk at the end of the motor makes the device customizable enough to work with 5-10 mm diameter shafts. Also based on the geometry of the very end of the shaft various impellers can be installed.

### Motor
The motor of the TMCS reactor system is a 24v DC motor which is driven and controlled by the power box and software. Due to the great importance of the resonance of the structure has passed various vibrational analyses in addition to dynamic and static tests. The current motor stall current is not more than 8A, but the power box can provide power for bigger motors (24V DC).

<p align="center"><a><img src="https://www.lambertmech.ir/project/pmdc/vibratoin-analysis.jpg" alt="Vibration Analysis" height="300" ></a></p>

### Power & driver box
This box is the heart of the system and allows the user to control the device with or without software. This box directly connects to a 220V power supplier and contains additional components to keep the device and user safe. Also for other lab applications, this box can be used as a 5V and 3A (max) power supplier. Moreover, when the computer is not connected user can set a specific rotational speed and by using the PID algorithm the speed will be fixed even if the composition's viscosity changes.

### Software
The TMCS software has various applications. The most significant application of this software is monitoring and saving the data in real time. Moreover, users can change the time constant of the PID controller. This software Do Not need any specific settings and just by connecting the USB port to the power box and setting the COM, it will run easily. In other words, when the computer is connected to the embedded processor will not do the controlling process and the CPU of the computer will do it in a more efficient way.

## Previous version
The previous version of the current TMCS was TMCS P10 which has lower efficiency and is not able to connect to the computer. The maximum rotational speed and torque of TMSC P10 are 300 rpm and 1.5 kg-cm respectively. The picture below indicates both devices (TMCS P21 and P10).

<p align="center"><a><img src="https://www.lambertmech.ir/project/pmdc/TMSC-P10-Label.jpg" alt="TMSC P10" height="300" ></a></p>

<p align="center"><a><img src="https://www.lambertmech.ir/project/pmdc/TMSC-P21-Label.jpg" alt="TMSC P21" style=“width:10%;” ></a></p>
