---
title: TMSC Reactor System
summary: A measurement device for controlling rotation speed of a laboratory reactor and monitor its torque in real time.

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
  name: Baspar Taban Arya
  url: http://lambertmech.ir/

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---



# TMSC Reactor System

The TMSC Reactor System is an advanced device designed for both stirring and monitoring viscosity changes in chemical reactions. It allows technicians to control reaction parameters efficiently. This versatile system can stir batches using various shafts and impellers at desired speeds, and it also monitors the implied torque from the composition inside the batch. 

Similar industrial assets without software cost over $1100, while our device offers a low-budget solution at about one third the price.

<p align="center"><a><img src="https://www.lambertmech.ir/project/pmdc/TMSC-P21.png" alt="TMSC P21" style="width:70%;" ></a></p>

## Properties
- **Speed:** 30-500 rpm
- **Torque:** up to 4.2 kg-cm
- **Shaft diameter:** 5-10 mm
- **Shaft length:** up to 50 cm
- **Input voltage:** 220 V
- **Maximum power:** 180 W

## Main Parts

### Shaft System and Speed Control
The motor's customizable chunk allows compatibility with shafts of 5-10 mm in diameter. Various impellers can be installed based on the shaft's geometry.

### Motor
The TMSC Reactor System uses a 24V DC motor controlled by a power box and software. The system has undergone vibrational, dynamic, and static tests to ensure stability. The motor's stall current is below 8A, and the power box supports higher current motors.

<p align="center"><a><img src="https://www.lambertmech.ir/project/pmdc/vibratoin-analysis.jpg" alt="Vibration Analysis" style="width:70%;" ></a></p>

### Power & Driver Box
The heart of the system, this box, connects to a 220V AC power source and allows control with or without software. It includes safety components and can also serve as a 5V, 3A power supplier for other lab applications. Users can set specific rotational speeds, maintained by a PID algorithm even with changing composition viscosity.

### Software
The TMSC software monitors and saves data in real-time, adjusts the PID controller's time constant, and requires no special settings. It runs efficiently by connecting the USB port to the power box and setting the COM, with the computer's CPU handling control processes when connected.

## Previous Version
The earlier TMSC P10 model had lower efficiency and couldn't connect to a computer. It had a maximum rotational speed of 300 rpm and torque of 1.5 kg-cm. Below are images of both the TMCS P21 and P10 models.

<p align="center"><a><img src="https://www.lambertmech.ir/project/pmdc/TMSC-P10-Label.png" alt="TMSC P10" style="width:60%;" ></a></p>

<p align="center"><a><img src="https://www.lambertmech.ir/project/pmdc/TMSC-P21-Label.png" alt="TMSC P21" style="width:70%;" ></a></p>