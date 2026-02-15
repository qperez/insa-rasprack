---
title: Home
layout: home
nav_order: 1
description: ""
permalink: /
---


# INSA Rasprack

### A small and transportable educative rack of machines
INSA Rasprack is a small 10-inch rack (5U) 3D printed and designed for teaching Computer Science. 
It is built using open-source plans and hardware.
This project was born out of the need to have multiple fully manageable machines, each with their own network, 
for teaching DevOps, IoT, and Linux systems. 
This website explains how the INSA Rasprack was created and what materials were required.

INSA Rasprack includes:
* 7 Raspberry Pi 3
* A Wi-Fi router
* A managed VLAN ethernet switch
* A 4-outlet power strip
* A 10-port USB hub

![Image of the 10 inches rack printed in 3D with a focus on the top of the rack 
where 7 raspebry pi card are stacked verically ](/insa-rasprack/assets/img/front_rack.jpg)

### From an idea to a concrete rack

The idea of INSA Rasprack has ermerged when I (Quentin Perez) see many Raspberry Pi cards sleeping in a 
hardware cabinet.
As a lecturer in Green Computing and a researcher on software energy consumption, it broke my heart to see this 
equipment lying idle and unused. Moreover, the network architecture at INSA Rennes did not allow me to have a 
dedicated network infrastructure for education, which would have given me full autonomy 
in my DevOps and IoT practical labs.
After seeing many "small lab racks" built by systems/network or software engineers using multiple Raspberry Pis, 
I realized there was a real opportunity with these devices. 
With the help of François Pasteau, I set out to build the INSA Rasprack.

### Contributors
* Quentin Perez, Associate Professor (PhD) of Software Engineering at INSA Rennes, France
* François Pasteau, Research Engineer (PhD) at INSA Rennes, France
* Thomas Voisin, 3D printing technician, INSA Rennes, France

### Bill of materials (BOM)

#### Hardware
INSA Rasprack is based on "low-cost" hardware available easily:

| Quantity | Description                              | Unit Price (VAT incl.) | Total Price (VAT incl.) | Link                                                                                                                                                       |
|----------|------------------------------------------|------------------------|-------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 7        | Raspberry Pi 3B+                         | €33.76                 | €236.32                 | [Digikey Link](https://www.digikey.com/en/products/detail/raspberry-pi/RASPBERRY-PI-3/6152799?src=raspberrypi)                                             |
| 7        | RJ45 Cable 0.5m                          | €4.25                  | €29.75                  | [RS Online Link](https://fr.rs-online.com/web/p/cables-ethernet/0411384)                                                                                   |
| 7        | USB 2.0 Cable, A MALE-B MALE, 0.5M       | €7.968                 | €55.78                  | [Farnell Link](https://fr.farnell.com/startech/usbaub50cmra/cable-usb-2-0-a-male-b-male-0/dp/3877694)                                                      |
| 1        | Wifi Router ASUS RT-AX53U                | €52.91                 | €52.91                  | [Amazon Link](https://www.amazon.fr/Asus-Routeur-WiFi-sans-RT-AX53U/dp/B099X58J8D?th=1)                                                                    |
| 1        | Ethernet Switch Zyxel GS1900-24e         | €97.92                 | €97.92                  | [Amazon Link](https://www.amazon.fr/-/en/Zyxel-Management-Lifetime-Warranty-GS1900-24E/dp/B09Q97VDPX?th=1)                                                 |
| 1        | Noctua NF-F12 5V                         | €24.90                 | €24.90                  | [Amazon Link](https://www.amazon.fr/-/en/Noctua-NF-F12-5V-High-End-Adapter/dp/B07DXLV5Z6)                                                                  |
| 1        | USB 3.0 Charging HUB 10 Port             | €46.99                 | €46.99                  | [Conrad Link](https://www.conrad.fr/fr/p/i-tec-u3chargehub10-hub-usb-10-ports-usb-a-usb-3-0-5-gbit-s-gris-i-tec-usb-3-0-charging-hub-10-port-3290709.html) |
| 1        | 4-outlet power strip rackable in 10 inch | €19.94                 | €19.94                  | [LDLC Link](https://www.ldlc.com/fiche/PB00160684.html)                                                                                                    |

**==> Total hardware VAT include: €564,51**

## 3D Models

We have reuse 3D printed models for the rack named "Lab Rax" created by [mkelement](https://makerworld.com/en/@mklements) and available on Makerworld: [Lab Rax 10 inch 5U server rack](https://makerworld.com/en/models/1294480-lab-rax-10-server-rack-5u#profileId-1325352)
Models have not been modified in terms of size, only small improvements has been done, we detail them in section
[improvements](#improvements)

The list of the parts needed to be printed are the following:
 
| Quantity | Part Name                             | Filament Type | Link                |
|----------|---------------------------------------|---------------|---------------------|
| 4        | 5U Brass Insert Vertical Post.3mf     | PETG          | [Vertical Post]()   |
| 4        | Horizontal Edge Vented.3mf (or solid) | PETG          | [Horizontal Edge](https://makerworld.com/en/models/1294480-lab-rax-10-server-rack-5u#profileId-1325352) |


### Building

#### 1) 3D Printing

Thomas Voisin has printed the models presented in section [3D Models](#3D-models) on a Prusa XL 3D printer.
Prusa XL is a "professional" printer but all the models are printable on printers like Creality Ender 3.

The printing time on Prusa XL is around 20 hours. 

#### 2) 

### Improvements

### Acknowledgment

A special thanks to the Computer Science department for granting this project of small and educative rack.
