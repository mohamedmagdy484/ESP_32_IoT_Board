# ESP32 4-Layer IoT Board 🚀
<img width="892" height="588" alt="3d" src="https://github.com/user-attachments/assets/754bb38f-4cc9-43fc-b499-4f9b7e7b1e76" />

A custom 4-layer hardware development board built around the **ESP32-WROOM** module. Designed to serve as a compact and versatile IoT platform featuring onboard sensors, display, battery power management, and expandable storage.
<img width="972" height="700" alt="Front" src="https://github.com/user-attachments/assets/3889bf35-1e8b-4524-bbb8-f5a381a4feaa" />
<img width="972" height="712" alt="Screenshot 2026-08-07 010526" src="https://github.com/user-attachments/assets/2998b69e-d7a0-4b3b-a7fc-c6b8ce9bcff7" />

---

## 📌 Features & Technical Specifications
<img width="1037" height="683" alt="all_Layers" src="https://github.com/user-attachments/assets/89f5c3b3-14da-471d-be3e-db442915048d" />

### 🧠 Core & Connectivity
* **Microcontroller:** ESP32-WROOM module (Wi-Fi & Bluetooth)
* **USB-to-UART:** CP2102N bridge with auto-programming circuitry for seamless flashing and serial debugging.

### ⚡ Power Management
* **Power Input:** USB Type-C interface with ESD protection.
* **Battery Charging:** Integrated **MCP73871** LiPo battery charger with Power Path Management.
* **Regulation:** High-efficiency 3.3V LDO regulator supplying stable power to digital and analog components.

### 🌡️ Onboard Sensors & Display
* **BME280:** Temperature, Humidity, and Pressure sensor.
* **TEMT6000:** Ambient light sensor.
* **Microphone:** Audio sensing circuit with pre-amplifier.
* **Display:** OLED display connector/interface.

### 💾 Storage & Memory
* **MicroSD Card:** Onboard MicroSD card slot for data logging.
* **External Flash:** Onboard SPI Flash memory.

---

### 🥞 PCB Layers Breakdown

#### Layer 1: Signal
<img width="897" height="652" alt="l1" src="https://github.com/user-attachments/assets/b7d29cc1-12aa-4361-8a37-bee441375226" />

#### Layer 2: Signal (contains all power polygon pours)
<img width="1015" height="712" alt="l2" src="https://github.com/user-attachments/assets/a5878118-137f-4c97-abab-dbba07c1c0e1" />

#### Layer 3: Plane (GND net)
<img width="997" height="681" alt="l3" src="https://github.com/user-attachments/assets/519d3667-bbd9-4e0c-bba1-741bc15415de" />

#### Layer 4: Signal
<img width="927" height="682" alt="l4" src="https://github.com/user-attachments/assets/e87fdcc7-5ac5-47fb-b20d-8948f348bdf5" />

---

## 🛠️ PCB Specifications

| Parameter | Specification |
| :--- | :--- |
| **Layer Count** | 4 Layers |
| **Layer Stackup** | Signal - Power-(Signal) - GND-(Plane) - Signal |
| **Power Distribution** | Continuous Ground Plane-Power is Signal Layer |
| **Design Tool** | Altium Designer |
