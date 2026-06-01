# SunPi2040 ☀️

This is my custom development board powered by the **RP2040** chip. 

Instead of just cheating and throwing a pre-made Raspberry Pi Pico or a Seeed XIAO onto a blank board, I wanted to learn how to route the actual raw microcontroller silicon entirely from scratch. 

It's built for my **Hack Club Macondo** hardware project!

## 🚀 What's on it?
* **RP2040 Microcontroller:**
* **LED** There's one LED that works as a status light
* **16MB Flash Memory:** (Winbond W25Q128) so I have plenty of space to flash scripts.
* **USB-C Port:** For power and data, because Micro-USB belongs in the trash.
* **AMS1117-3.3V:** To drop the USB power down safely so the chip doesn't explode.
* **Pin Headers:** Two rows of 20-pin headers so I can actually plug this into a breadboard.

The PCB was designed using KiCAD, and I went from never even touching hardware design to creating this devboard. Along the way, I struggled with lots of issues like DRC errors and terrible routing where I met a lot of dead ends.
I created this project in order to learn how to work with KiCAD and hardware design, so that I can work on another project which is a game console-style project.
I found PCB easter eggs quite amusing, and so I decided to include a bunch of PCB easter eggs at the back.

Pictures of the Devboard:

<img width="1112" height="966" alt="Screenshot 2026-06-01 at 12 27 57 AM" src="https://github.com/user-attachments/assets/6d7b687c-7dc8-4062-9d63-701ff6a50a31" />
<img width="772" height="913" alt="Screenshot 2026-06-01 at 12 28 18 AM" src="https://github.com/user-attachments/assets/77725a36-c3e3-4ded-bb07-ada03411665f" /><img width="1706" height="987" alt="Screenshot 2026-06-01 at 12 28 43 AM" src="https://github.com/user-attachments/assets/898aa0d2-6894-43e4-b823-0bfa9c5acc1f" />

I tried to optimise the parts used, and have to do PCBA on both sides because I don't own a soldering iron. Also, the RP2040 is really hard to hand solder.

<img width="1051" height="848" alt="Screenshot 2026-06-01 at 5 27 14 PM" src="https://github.com/user-attachments/assets/972d55c5-06ee-452d-8827-2a3cffd112f6" />

<img width="1220" height="716" alt="Screenshot 2026-06-01 at 5 29 56 PM" src="https://github.com/user-attachments/assets/9da89503-585d-466d-b570-96352e2fd463" />




Open source, feel free to check out my schematics or tell me where my routing looks messy.
