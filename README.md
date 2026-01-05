# Aduino-VALOAI
# VALOAI

**VALOAI** is a free AI aimbot that uses object detection to automatically target enemies and deliver instant headshots when you press the **ALT** key.  
It works **without modifying any game files**, sending input directly to an **Arduino Leonardo**.

> **NB:** VALOAI is **open-source**, so you can customize it to your needs.

---

## ⚙️ Requirements

### Hardware
- Arduino **Leonardo**
- **USB Host Shield 2.0** (make sure it is soldered correctly)

### Notes on Detection
- Anti-cheat systems *could* flag Arduino Leonardo boards, but this is unlikely since it behaves like a standard mouse.
- Excessive player reports may trigger **manual review** by Riot, which can result in a ban.  
  **Use responsibly.**

---

## 🛠️ Setup Instructions

### 1. Hardware Setup
- Attach the USB Host Shield to the Arduino
- Connect the Arduino to your computer via USB
- Ensure it is connected to **COM3** (or update the port in the code)

### 2. Upload Arduino Code
- Open **Arduino IDE**
- Load the provided Arduino script
- Upload it to the Arduino Leonardo

### 3. Run Python Script
- Open **CMD / Terminal**
- Navigate to the project folder
- Run:
  ```bash
  python aimbot.py
