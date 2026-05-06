<div align="center">

# ⚡ Shivani Narola

**Embedded Systems Engineer · Firmware Developer · Hardware Hacker**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:narolashivanip@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com)

</div>

---

## 👩‍💻 About Me

```c
typedef struct {
    char *name        = "Shivani Narola";
    char *role        = "Embedded Systems Engineer";
    char *education   = "B.Tech Electrical Engineering @ IITRAM (2022–2026)";
    float cpi         = 8.36;
    char *focus[]     = { "Firmware Development", "Low-Level Programming",
                          "RTOS", "Hardware Interfacing", "Linux Drivers" };
} Engineer;
```

I work close to the metal — writing firmware, building bootloaders, and talking directly to hardware registers. My interest lies in making embedded systems reliable, efficient, and production-ready.

---

## 🛠️ Technical Stack

**Languages**

![C](https://img.shields.io/badge/Embedded_C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-6E4C13?style=flat-square)

**Microcontrollers & Hardware**

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)

**Protocols & Interfaces**

![UART](https://img.shields.io/badge/UART-555?style=flat-square)
![SPI](https://img.shields.io/badge/SPI-555?style=flat-square)
![I2C](https://img.shields.io/badge/I2C-555?style=flat-square)
![TCP/IP](https://img.shields.io/badge/TCP%2FIP-555?style=flat-square)
![GPIO](https://img.shields.io/badge/GPIO-555?style=flat-square)
![SWD/JTAG](https://img.shields.io/badge/SWD%2FJTAG-555?style=flat-square)

**Tools & IDEs**

![STM32CubeIDE](https://img.shields.io/badge/STM32CubeIDE-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-6DB33F?style=flat-square)
![Arduino IDE](https://img.shields.io/badge/Arduino_IDE-00979D?style=flat-square&logo=arduino&logoColor=white)

---

## 🚀 Featured Projects

### 🔄 STM32 Over-the-Air (OTA) Firmware Update System
> `STM32F103` · `W25Q32 SPI Flash` · `UART DMA` · `ESP8266` · `CRC32` · `Embedded C`

A custom bootloader and OTA pipeline built entirely from scratch on bare-metal STM32.

- ⚡ Boot & vector table relocation in **< 200ms** with a **16KB** memory footprint
- 🔒 CRC32 validation catches **100%** of corrupted firmware before flash write
- 📡 Downloads firmware at **115200 baud** via UART DMA into 32Mb external SPI flash
- 🔌 Modular design — accepts updates from Internal Flash, SPI Flash, or Network

---

### 🧠 IoT Health & Safety Wearable for Alzheimer's Care
> `ESP32` · `FreeRTOS` · `MPU6050` · `MAX30102` · `NEO-6M GPS` · `I2C/UART` · `Blynk Cloud`

A real-time wearable system with RTOS-based multitasking for continuous health monitoring.

- 🏃 Preemptive FreeRTOS scheduling with Binary Semaphores for **sub-millisecond** fall detection
- 📡 Thread-safe WiFi telemetry using Queues & Mutexes — no resource contention
- 💓 Moving-average filters and peak-detection for biometric (SpO₂/HR) reliability

---

### 🐧 MPU6050 Multi-Axis Linux Kernel Driver
> `Linux Kernel` · `I2C` · `Sysfs` · `Mutex` · `Raspberry Pi` · `ktime`

A from-scratch Linux kernel module exposing IMU data through the Sysfs interface.

- 📁 Maps raw 16-bit sensor registers to virtual files at `/sys/kernel/mpu6050/`
- 🔐 Mutex synchronization ensures thread-safe multi-axis reads
- ⏱️ Measured consistent driver latency of **~2.1 ms** using `ktime`

---

*"The closer you are to the hardware, the more you understand what software really does."*

![Visitor Count](https://komarev.com/ghpvc/?username=shivani-narola&color=blue&style=flat-square)

</div>
