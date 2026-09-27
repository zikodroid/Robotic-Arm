# 🦾 2-DOF Mechatronic Robotic Arm - Rotary Base (Phase 1)

Welcome to my small Workshop! here i share everything about my custom-designed mechatronic robotic arm project. **This project is currently under active development.** The current release represents **Phase 1**, focusing on the precision rotary base and mechanical gear integration, achieving an exceptional movement accuracy of **99%**.

---

## 🚀 Project Overview & Current Status
* **Current Status:** 🚧 Under Development (Phase 1 Complete: Rotary Base & Actuation).
* **Objective:** Design, 3D print, and program a high-precision, low-cost mechatronic robotic arm with Automation & wireless control.
* **Core Performance:** Achieved **99% movement accuracy** through precise calibration and hardware-software integration.
* **Core Technologies:** Autodesk Inventor, 3D Printing (PLA/PETG), ESP32 Microcontroller, C++, and custom wireless communication.

---
![CAD Render Design](https://github.com/zikodroid/Robotic-Arm/blob/main/Media/Base_Getriebe_2%20-%20Kopie.png)
![Real Photo](https://github.com/zikodroid/Robotic-Arm/blob/main/Media/Base_Getriebe_1.png)
---

## 📂 Repository Structure
* `/Media` - Contains short demonstration videos (.mp4), and hardware test footage.
* `/Models` - Includes CAD renders, STEP/STL files, and 3D printing configurations.

---

## 🎥 Assembly & Test Videos
[![Assembly Video](https://img.youtube.com/vi/WgQ9TpypU44/hqdefault.jpg)](https://www.youtube.com/watch?v=WgQ9TpypU44)
---
## 💻 Source Code & Library Dependency
* **[Operating Code](https://github.com/zikodroid/controlStepperWithXbox.git):** Contains the core C++ operational code for the ESP32 controlling the rotary base.
* **[Custom XBOX-ESP32 Link Library](https://github.com/zikodroid/ESP-XBOX-link.git):** Contains the dedicated custom-built library to connect the XBOX Controller with ESP32 (Mandatory with the Previous Code)
---

## 🛒 Hardware Components & Bill of Materials (BOM)
Here are the core components used to build the Phase 1 rotary base and control system:

* **Microcontroller:** [ESP32-S3 / Development Board](https://amzn.eu/d/0c9y7wGY)
* **Stepper Motor:** [NEMA 17 Stepper Motor](https://amzn.eu/d/09fnmTch)
* **Magnetic Encoder:** [AS5600 Magnetic Encoder](https://amzn.eu/d/068zWkTg)
* **Controller:** [Xbox Wireless Controller](https://amzn.eu/d/0i4OwxBr)
* **Ball Bearings 20x27x4:** [Ball Bearings 20x27x4](https://amzn.eu/d/06Etchw0)
* **Ball Bearings 10x19x5:** [Ball Bearings 10x19x5](https://amzn.eu/d/0ethZim4)
* **Brass Inserts M3:** [Brass Inserts M3](https://amzn.eu/d/01GirjP7)
* **M3 Screws (Example):** [M3 Screws](https://amzn.eu/d/00yubzFb)

---

## ⚙️ Key Technical Features
1. **Mechanical Design & CAD:** Engineered using Autodesk Inventor, featuring custom 3D-printed worm gearboxes and optimized tolerances for additive manufacturing.
2. **Embedded Firmware:** Developed in C++ to process real-time inputs, managing closed-loop feedback and achieving **99% motion accuracy**.
3. **Wireless Integration:** Seamless communication architecture connecting the user input layer directly to the mechatronic hardware.

---
