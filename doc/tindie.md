# TFGPSLITE02 - Compact GNSS Module for UAVs

A lightweight GNSS module with a high-quality ground plane, ideal for UAVs, multirotors, planes, and balloons.


The TFGPSLITE02 is a compact and lightweight open-source hardware GNSS module based on the u-blox SAM-M8Q receiver. Designed for small UAVs and simple navigation applications, it offers precise positioning with support for GPS, Galileo, and GLONASS constellations.

One of its key advantages is the integrated ground plane—a conductive surface beneath the antenna that improves signal quality and reduces interference. This feature ensures more stable and accurate positioning, especially in UAV applications where signal integrity is critical.

With seamless integration via the Pixhawk Basic GPS Port, this module is an excellent choice for developers and hobbyists looking for a simple yet effective GNSS solution.

## Open-Source & Customizable

The TFGPSLITE02 is open-source hardware, allowing engineers, developers, and UAV enthusiasts to modify, improve, and adapt the design to their specific needs. Design files, schematics, and firmware resources are publicly available in the project’s repository.

---

## Key Features
- **Multi-GNSS Support** – Receives GPS, Galileo, and GLONASS signals for increased accuracy.
- **Compact and Lightweight** – Weighing only **11.3 grams**, ideal for weight-sensitive UAV applications.
- **High-Quality Ground Plane** – Improved signal reception compared to low-cost GNSS modules.
- **Reliable Performance in Challenging Environments** – Works in areas with weak GNSS signals.
- **Support for SBAS and QZSS** – Enhances positioning accuracy.
- **Advanced Security Features**:
  - Geofencing support
  - Spoofing detection
  - Message integrity protection
- **Built-in RTC (Real-Time Clock)** – Reduces Time-To-First-Fix after power loss.
- **Wide Operating Range**:
  - Up to **50,000m altitude**, **500m/s velocity**, and **4g dynamic tolerance**.

---

## Technical Specifications
- **Receiver**: u-blox SAM-M8Q GNSS module
- **Interfaces**:
  - UART and I2C (via Pixhawk Basic GPS Port)
  - 1PPS time pulse output (configurable up to 10 MHz)
- **Power Requirements**:
  - Voltage: **5V**
  - Typical power consumption: **30mA**
- **Positioning Performance**:
  - Cold start TTFF: **26s** (GPS)
  - Hot start TTFF: **1s**
  - Accuracy: **2.5m CEP**
- **Environmental Ratings**:
  - Operating temperature: **-40°C to +85°C**
  - Storage temperature: **-40°C to +85°C**
- **Physical Dimensions**:
  - **50mm × 50mm × 8mm**
  - **Weight: 11.3g**

---

## Easy Integration with UAV Systems
The TFGPSLITE02 connects to flight controllers via the **Pixhawk Basic GPS Port**, ensuring hassle-free setup. The pinout is:

| Pin | Signal  | Voltage |
|-----|--------|---------|
| 1   | VCC    | 5V     |
| 2   | TX (OUT) | 3.3V   |
| 3   | RX (IN) | 3.3V   |
| 4   | I2C SCL | 3.3V   |
| 5   | I2C SDA | 3.3V   |
| 6   | GND    | GND    |

It also supports external payload connections for additional signals.


