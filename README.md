# 🌿 ECOSYNC – An Automated Intelligent AC Temperature Regulator

![ECOSYNC Banner](images/banner.png) <!-- Replace with your own image -->

ECOSYNC is a smart embedded system designed to **optimize air-conditioning energy usage in hotel rooms** without compromising guest comfort. It directly supports Sri Lanka’s energy conservation goals by dynamically adjusting AC temperature based on guest presence — striking a balance between **technical innovation**, **user-centric design**, and **business practicality**.

---

## 🎯 Project Summary

> 🏨 **"Hotels in Sri Lanka face significant electricity costs, with air conditioning being a major contributor."**  
> ECOSYNC reduces waste by monitoring room occupancy via **keycard presence**, automatically switching AC modes when the guest leaves — all without manual staff input.

- 📆 **Timeline:** Aug 2024 – Jun 2025  
- 🎓 **Institution:** University of Moratuwa  
- 📂 **Project Type:** Academic + Entrepreneurial Capstone

---

## 🔧 Key Features

| Component                     | Description                                                                 |
|------------------------------|-----------------------------------------------------------------------------|
| **Microcontroller**          | ATmega328P-PU-based embedded system                                         |
| **Communication**            | Bluetooth (HC-05 & HC-06 modules)                                           |
| **AC Control**               | IR emitter-based transmission of control signals to AC units                |
| **Presence Detection**       | IR-based keycard detection (no motion sensors needed)                       |
| **Custom PCBs**              | Designed in Altium Designer, housed in 3D printed enclosures                |
| **Modular Design**           | Two-unit system: Keycard Presence Detector (KPD) and AC Controller (ACC)    |
| **Power Modes**              | - *Eco Mode:* Raise to 25°C  
                               - *Luxury Mode:* Raise to 23°C on vacancy                                    |

---

## 🧠 How It Works

1. **Guest inserts/removes room keycard**
2. KPD detects presence → sends Bluetooth signal to ACC
3. ACC adjusts AC using IR signals based on mode preset
4. Temperature changes to save power when room is unoccupied

> All logic and control are handled internally on the embedded system — no cloud dependency.

---

## 🏆 Achievements

- 🥈 **Runners-up** – *Techno Spark 2024*, Startup Challenge by IESL  
- 🥈 **Runners-up** – *GAP Circularity Challenge 2025*, organised by INSEE  
- 🥉 **2nd Runners-up** + 🏆 *Most Popular Innovation* – *Future Innovation Challenge 2025*, IEEE Student Branch  

---

## 💼 Leadership & Contributions

- 👨‍💼 **Role:** Team Leader  
  - Led project coordination, pitch development, and strategy  
  - Oversaw brand identity and presentation materials  
- 🛠️ **Technical Contribution:**  
  - Designed second-gen PCBs for KPD and ACC modules  
  - Refined embedded logic and system-level integration  
  - Contributed to go-to-market planning: mobile control, AI scheduling, and voice automation

---

## 💼 Business Model & Sustainability

- **Target Market:** Hotels and resorts with centralized or individual room AC units  
- **Revenue Streams:**
  - Installation + hardware cost  
  - Subscription for maintenance/updates  
  - Energy efficiency consulting services

> Designed to scale across hospitality infrastructure while contributing to Sri Lanka’s sustainable energy transition.

---

## 🛠️ Tech Stack

- **Hardware:** ATmega328P-PU, IR Sensors, Bluetooth (HC-05/HC-06), Custom PCBs  
- **Design Tools:** Altium Designer, Fusion 360 (for enclosures), Arduino IDE  
- **Communication:** Serial Bluetooth, IR protocols for major AC brands

---

## 📷 Media

| Device | System Diagram | Prototype Demo |
|--------|----------------|----------------|
| ![Device](images/device_photo.jpg) | ![Diagram](images/system_diagram.png) | ![Demo](images/demo_photo.gif) |

---

## 🙋 About the Developer

Third-year Electronics & Telecommunication Engineering undergraduate at the University of Moratuwa. Focused on analog and mixed-signal circuit design, with experience in PCB development, simulation, and hardware integration. Currently exploring open-source IC tools and machine learning as a secondary interest. Passionate about sustainable tech solutions and hardware innovation.

---

## 🤝 Contact

- 📬 Reach out via [LinkedIn](https://www.linkedin.com/in/yourprofile) or open an Issue on this repository.  
- 📄 Full project pitch deck: [`ECOSYNC_Pitch.pdf`](./docs/ECOSYNC_Pitch.pdf)

---

