<p align="center">
  <img src="images/ecosync-logo.png" alt="ECOSYNC Logo" width="200"/>
</p>

<h1 align="center">ECOSYNC</h1>
<h3 align="center">An Automated Intelligent AC Temperature Regulator</h3>

<p align="center">
  <img src="images/socketburners-logo.png" alt="SocketBurners Logo" width="120"/>
  <br/>
  <strong>Team SocketBurners – University of Moratuwa</strong>
</p>

---

## 🌿 Overview

**ECOSYNC** is a smart embedded system designed to optimize energy usage in hotel rooms without compromising guest comfort. It contributes to Sri Lanka’s energy conservation goals by dynamically adjusting AC temperature based on guest presence. When the room is unoccupied, ECOSYNC conserves energy automatically — improving sustainability and reducing operating costs.

---

## 🎯 Why It Matters

Sri Lanka continues to face energy shortages, and hotels consume a significant portion of their energy on air conditioning alone.

> “Our hotel pays an average of LKR 9,800,000 per month on electricity. During test runs, optimizing AC usage reduced costs by up to 60%.”  
> — *Mr. Akila, Lead Maintenance Engineer, Sophia Hotel Colombo*

---

## 🔧 Key Features

| Feature                     | Description                                                                  |
|----------------------------|------------------------------------------------------------------------------|
| **Embedded Controller**    | ATmega328P-PU microcontroller-based system                                   |
| **Wireless Control**       | Bluetooth (HC-05 & HC-06) for KPD ↔ ACC communication                        |
| **AC Interface**           | IR emitter-based control for compatibility with common AC brands             |
| **Smart Presence Detection**| IR-based keycard detection (avoids motion sensors)                          |
| **Custom PCBs**            | Designed in Altium, housed in 3D printed enclosures                          |
| **Two Modes**              | Eco Mode (25°C) and Luxury Mode (23°C) when guest is away                    |

---

## ⚙️ How It Works

1. Guest inserts/removes the room keycard.
2. KPD detects presence and transmits signal to the AC Controller (ACC) via Bluetooth.
3. ACC adjusts temperature settings using IR based on hotel-defined presets.
4. When guest returns, temperature resumes previous setting for comfort.

---

## 🧠 Technical Stack

- **MCU:** ATmega328P-PU
- **Bluetooth:** HC-05 (KPD), HC-06 (ACC)
- **IR Modules:** TSOP + IR LEDs
- **Design Tools:** Altium Designer, Arduino IDE
- **Enclosure:** 3D printed cases (Fusion 360)
- **Languages:** Embedded C (Arduino)

---

## 📈 Achievements

🏆 This project was recognized in multiple national-level innovation competitions:

- 🥈 **Runners-up** – Techno Spark 2024 (IESL)  
- 🥈 **Runners-up** – GAP Circularity Challenge 2025 (INSEE)  
- 🥉 **2nd Runners-up** + 🏆 *Most Popular Innovation* – Future Innovation Challenge 2025 (IEEE Student Branch)  

---

## 📦 Business Model

| Revenue Stream                     | Description                                                             |
|------------------------------------|-------------------------------------------------------------------------|
| Installation Fees                  | Per-room installation and hardware deployment                          |
| Subscription/Maintenance          | Software updates, analytics, troubleshooting                           |
| Energy Efficiency Consulting       | Tailored audits for hotel partners                                     |
| Partnerships                       | HVAC integrators, property managers, hotel suppliers                    |

---

## 🚀 Future Vision

- 📍 Expand to additional hotel chains and public buildings  
- 🔬 Integrate AI-powered dynamic scheduling and temperature optimization  
- 📱 Add support for mobile app control and voice assistants  
- 🌐 Commercial licensing for building automation platforms

---

## 🧑‍💻 Role and Contributions

**Led by:** Team Leader – [Your Name]  
- Coordinated team efforts and technical planning  
- Designed the improved PCB versions for KPD and ACC  
- Developed project brand, pitch strategy, and business roadmap  
- Presented the project at multiple competitions and demo days

---

## 🖼️ Screenshots & Media

| Prototype Unit | System Diagram | Demo Installation |
|----------------|----------------|-------------------|
| ![Device](images/device-photo.jpg) | ![Diagram](images/system-diagram.png) | ![Demo](images/demo.gif) |

---

## 🙋 About the Developer

Third-year Electronics & Telecommunication Engineering undergraduate at the University of Moratuwa. Focused on analog and mixed-signal circuit design, with experience in PCB development, hardware simulation, and system integration. Currently exploring open-source IC tools and machine learning as secondary interests.

---

## 📄 Documentation

- 📂 [Pitch Deck (PDF)](docs/ECOSYNC_Pitch.pdf)  
- 📁 PCB schematics and source code (see folders above)

---

## 📬 Contact

Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/yourprofile) or open an issue in this repo.

---

<p align="center">
  <em>Designed with purpose. Built for sustainability. Engineered by SocketBurners.</em>
</p>
