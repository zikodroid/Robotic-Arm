# Mechatronic Robotic Arm by Z.Moustafa 🦾
# Rotary Base (Phase 1)

Welcome to my small Workshop! here i share everything about my custom-designed mechatronic robotic arm project. **This project is currently under active development.** The current release represents **Phase 1**, focusing on the precision rotary base and mechanical gear integration, achieving an exceptional movement accuracy of **99%**.

---

About Me:
An ambitious Mechanical Engineer with a strong passion for Robotics & transforming complex Mechatronic concepts into precise, high-performance real-world applications. Experienced in CAD design, 3D printing optimization, Programming and embedded systems development. Dedicated to building innovative, intelligent engineering solutions and smart mechatronic systems.

📧 Contact: [z.moustafa.205@gmail.com]
             [zikodroid@gmail.com]

---

## 🚀 Project Overview & Current Status
* **Current Status:** 🚧 Under Development (Phase 1 Complete: Rotary Base & Actuation).
* **Objective:** Design, 3D print, and program a high-precision, low-cost mechatronic robotic arm with Automation & wireless control.
* **Core Performance:** Achieved **99% movement accuracy** through precise calibration and hardware-software integration.
* **Core Technologies:** Autodesk Inventor, 3D Printing (PLA/PETG), ESP32 Microcontroller, C++, and custom wireless communication.

---

<table align="center" style="border: none;">
  <tr>
    <td align="center" style="padding: 10px; border: none;">
      <img src="https://zikodroid.github.io/Robotic-Arm/Media/Base_Getriebe_2.png" alt="CAD Render Design" width="400">
      <br>
      <em>Figure 1: CAD Design</em>
    </td>
    <td align="center" style="padding: 10px; border: none;">
      <img src="https://zikodroid.github.io/Robotic-Arm/Media/Real_Photo.png" alt="Real Hardware" width="400">
      <br>
      <em>Figure 2: Assembled Prototype</em>
    </td>
  </tr>
</table>

---

## 🎥 Assembly & Test Videos
[![Assembly Video](https://img.youtube.com/vi/WgQ9TpypU44/hqdefault.jpg)](https://www.youtube.com/watch?v=WgQ9TpypU44)
[![Assembly Video](https://img.youtube.com/vi/2EUBBXBF5gc/hqdefault.jpg)](https://www.youtube.com/shorts/2EUBBXBF5gc)
[![Assembly Video](https://img.youtube.com/vi/UMWc8HyBJto/hqdefault.jpg)](https://www.youtube.com/shorts/2EUBBXBF5gc)

---

## 📂 Repository Structure
* `/Media` - Contains short demonstration videos (.mp4), and hardware test footage.
* `/Models` - Includes CAD renders, STEP/STL files, and 3D printing configurations.
* Download the Files here: **[Main Repository](https://github.com/zikodroid/Robotic-Arm.git)

---

## 🛒 Hardware Components & Bill of Materials (BOM)
Here are the core components used to build the Phase 1 rotary base and control system:

* **Microcontroller:** [ESP32-S3 / Development Board](https://amzn.eu/d/0c9y7wGY)
* **Stepper Motor:** [NEMA 17 Stepper Motor](https://amzn.eu/d/09fnmTch)
* **Magnetic Encoder:** [AS5600 Magnetic Encoder](https://amzn.eu/d/068zWkTg)
* **Controller:** [Xbox Wireless Controller](https://amzn.eu/d/0i4OwxBr)
* **Stepper Motor Driver:** [Stepper Motor Driver](https://amzn.eu/d/00BdDssQ)
* **Ball Bearings 20x27x4:** [Ball Bearings 20x27x4](https://amzn.eu/d/06Etchw0)
* **Ball Bearings 10x19x5:** [Ball Bearings 10x19x5](https://amzn.eu/d/0ethZim4)
* **Brass Inserts M3:** [Brass Inserts M3](https://amzn.eu/d/01GirjP7)
* **M3 Screws (Example):** [M3 Screws](https://amzn.eu/d/00yubzFb)

---

## 💻 Source Code & Library Dependency
* **[Operating Code](https://github.com/zikodroid/controlStepperWithXbox.git):** Contains the core C++ operational code for the ESP32 controlling the rotary base.
* **[Custom XBOX-ESP32 Link Library](https://github.com/zikodroid/ESP-XBOX-link.git):** Contains the dedicated custom-built library to connect the XBOX Controller with ESP32 (Mandatory with the Previous Code)

---

## ⚙️ Key Technical Features
1. **Mechanical Design & CAD:** Engineered using Autodesk Inventor, featuring custom 3D-printed worm gearboxes and optimized tolerances for additive manufacturing.
2. **Embedded Firmware:** Developed in C++ to process real-time inputs, managing closed-loop feedback and achieving **99% motion accuracy**.
3. **Wireless Integration:** Seamless communication architecture connecting the user input layer directly to the mechatronic hardware.

---
