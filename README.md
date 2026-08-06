# ESP32 4-Layer IoT Board 🚀
<img width="892" height="588" alt="3d" src="https://github.com/user-attachments/assets/754bb38f-4cc9-43fc-b499-4f9b7e7b1e76" />

A custom 4-layer hardware development board built around the **ESP32-WROOM** module. Designed to serve as a compact and versatile IoT platform featuring onboard sensors, display, battery power management, and expandable storage.

---

## 📌 Features & Technical Specifications

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

## 🛠️ PCB Specifications

| Parameter | Specification |
| :--- | :--- |
| **Layer Count** | 4 Layers |
| **Layer Stackup** | Signal - Power-(Signal) - GND-(Plane) - Signal |
| **Power Distribution** | Continuous Ground Plane-Power is Signal Layer |
| **Design Tool** | Altium Designer |
