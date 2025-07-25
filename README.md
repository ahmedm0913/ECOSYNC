<p align="center">
  <img src="ECOSYNC.png" alt="ECOSYNC Logo" width="500"/>
</p>

<h1 align="center">ECOSYNC</h1>
<h3 align="center">An Automated Intelligent AC Temperature Regulator</h3>

<p align="center">
  <img src="SocetBurners.png" alt="SocketBurners Logo" width="300"/>
  <br/>
  <strong>Team SocketBurners – University of Moratuwa</strong>
</p>

---

## 🌿 Overview

**ECOSYNC** is an intelligent AC temperature regulator designed for hotel rooms. It dynamically adjusts the air conditioning temperature based on room occupancy, optimising energy usage without compromising guest comfort.

The system uses a **Keycard Presence Detector (KPD)** to detect guest presence and a paired **Air Conditioner Controller (ACC)** to communicate with the AC unit using IR signals. Together, they enable room-level energy conservation in real-time, providing fully automated control.

---

## 🔧 Key Features

- 🔌 IR-based AC control for most commercial brands
- 📶 Bluetooth communication between modules (HC-05 & HC-06)
- 🧠 Embedded control using ATmega328P-PU microcontrollers
- 🛠️ Fully custom PCBs (Altium), housed in 3D printed enclosures
- 🧩 Modular design: KPD and ACC work as standalone units or as a system
- 🌡️ Two preset energy modes: 25°C (Eco) and 23°C (Luxury)

---

## ⚙️ Functionality

The system works as follows:

1. Guest removes the keycard → KPD detects absence.
2. KPD transmits a signal via Bluetooth to the ACC.
3. ACC sends IR signals to increase the room temperature.
4. When the guest returns, normal AC behaviour resumes.

<p align="center">
  <img src="Final.png" width="1000"/>
</p>

---

## 🧩 Printed Circuit Boards

### 🔷 Keycard Presence Detector (KPD)

- **Top View**  
  <p align="center"><img src="sm_black_top (1).png" alt="KPD PCB" width="500"/></p>

- **Bottom View**  
  <p align="center"><img src="sm_black_bottom (1).png" alt="KPD Bottom View" width="500"/></p>

---

### 🔶 AC Controller (ACC)

- **Top View**  
  <p align="center"><img src="sm_black_top.png" alt="ACC Top View" width="500"/></p>

- **Bottom View**  
  <p align="center"><img src="sm_black_bottom.png" alt="ACC Bottom View" width="500"/></p>

---

## 🗂️ Schematics

- **KPD Schematic**  
  <p align="center"><img src="kpd_schem.png" alt="KPD Schematic" width="800"/></p>

- **ACC Schematic**  
  <p align="center"><img src="acc_schem.png" alt="ACC Schematic" width="800"/></p>
---

## 🖼️ Final Prototype Photos

- **Assembled Devices**

<p align="center">
  <img src="IMG-20240829-WA0019.jpg" width="48%"/>
  <img src="IMG-20240829-WA0081.jpg" width="48%"/>
</p>

---

## Experience

We began this project during our **second semester**, starting with basic concepts and gradually building a working prototype.  

- We **visited Sophia Hotel in Colombo** to gather real user observations and insights from their maintenance engineers.  
- Our **initial design faced dimension issues**, which taught us valuable lessons in hardware integration and enclosure design.  
- We redesigned the PCBs and casing to create a **robust and reliable second-generation prototype**.  
- The project involved many **overnight development sessions**, balancing technical work and team coordination.  

---

## 🏆 Awards & Achievements

- 🥈 **1st Runner-up** – IESL Techno Spark Startup Competition 2024  
- 🥈 **1st Runner-up** – GAP Circularity Challenge 2025 (Organized by INSEE)  
- 🥉 **2nd Runner-up** – Future Innovators Challenge 2025 (IEEE Student Branch, UoM)  
- 🏆 **Most Popular Innovation** – Future Innovators Challenge 2025 (IEEE Student Branch, UoM)  
- 🎖️ **Finalists** – IESE Grant Scheme 2025  

---

## 🎬 Demo Video & Website

- 📹 **Watch the Full Demo Video:**  
  🔗 [ECOSYNC Demo Video](https://drive.google.com/file/d/1JfGw0Y93dIrog_j1LMHH4Kcrz3Ky19dq/view?usp=sharing)

- 🌐 **Visit Our Project Website:**  
  🔗 [ECOSYNC Website](https://nadha.my.canva.site/ecosyn-socketburners)

---

## 👤 My Role

- 👥 Leading and managing the team  
- 🛠️ PCB design (KPD & ACC)  
- 🎨 Brand designing and identity creation  
- 💼 Business pitching and strategy  

---

## 🧑‍💻 Team & Credits

**Team:** SocketBurners  
3rd Year Electronics & Telecommunication Engineering Undergraduates  
**University of Moratuwa**

<p align="center">
  <img src="484904085_122127235142612800_2873341187870754367_n (1).jpg" alt="Team SocketBurners" width="500"/>
  <br/>
  <em>Team SocketBurners</em>
</p>

---

<p align="center">
  <em>Built for energy efficiency. Engineered by SocketBurners.</em>
</p>

