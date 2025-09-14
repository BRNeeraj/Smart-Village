# 🌐 Smart Village Network (Cisco Packet Tracer)

## 📌 Project Overview
This project demonstrates the implementation of a **Smart Village Network** using Cisco Packet Tracer.  
It integrates **IoT devices** with networking infrastructure to provide automation, monitoring, and control for different areas of a village:
- 🏠 Smart Home  
- 🏥 Smart Hospital  
- 🏫 Smart School  
- 🌱 Smart Irrigation  

The goal is to simulate how IoT and networking can be combined to improve the quality of life, healthcare, education, and agriculture in rural areas.

---

## 🖥️ Devices Used
### Core Network
- **IoT Server** (Server-PT)  
- **Main Switch** (2960 Switch)  
- **Cloud (ISP_Cloud)** for WAN connectivity  

### Smart Home
- RFID Card & Reader  
- Smartphone  
- Smart Door  
- Smart Light  
- Motion Detector  
- Smart Fan  
- Garage Door  
- Home Gateway  

### Smart Hospital
- PC  
- Motion Detector  
- Webcam Camera  
- Temperature Monitor  
- Air Conditioner  
- Wireless Access Point  

### Smart School
- Tablet PC  
- Motion Detector  
- Smart Light  
- Smart Door  
- Smart Window  
- Webcam Camera  
- Wireless Access Point  

### Smart Irrigation
- Laptop  
- Water Level Monitor  
- Lawn Sprinklers (2)  
- Temperature Monitor  
- Wireless Access Point  

---

## 🌐 Network Topology
The Smart Village is divided into **four functional areas**, each connected via a **centralized switch and IoT server**:
- The **IoT Server** manages device registration and automation rules.  
- Each zone (home, hospital, school, irrigation) connects through an **Access Point or Home Gateway** for IoT device communication.  
- The **Main Switch** connects all zones, the IoT server, and the ISP Cloud.  
<img width="2641" height="802" alt="1" src="https://github.com/user-attachments/assets/9dcb5748-56ad-41d1-8a19-ad93ec92bc1d" />

<p align="center">
<img width="2641" height="802" alt="1" src="https://github.com/user-attachments/assets/9dcb5748-56ad-41d1-8a19-ad93ec92bc1d" />
</p>

---

## ⚙️ Features & Automation
- **Smart Home**: RFID-based door access, motion-based lighting, garage automation, and fan control.  
- **Smart Hospital**: Environmental monitoring (temperature), motion detection, air conditioning, and remote surveillance via webcams.  
- **Smart School**: Security with motion sensors, smart lighting, automated doors/windows, and camera monitoring.  
- **Smart Irrigation**: Automatic sprinkler system controlled by **water level** and **temperature sensors**.  

---

## 🚀 How to Run

### Clone the Repository
```bash
# Clone this repository
git clone https://github.com/<your-username>/SmartVillage-Network.git

# Enter into the project folder
cd SmartVillage-Network


## 🏷️ Tags
`#CiscoPacketTracer` `#IoT` `#Networking` `#SmartVillage` `#SmartHome` `#SmartHospital` `#SmartSchool` `#SmartIrrigation`
