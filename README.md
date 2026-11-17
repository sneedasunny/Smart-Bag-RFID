# 🎒 SmartBag – RFID-Based Smart Bag

An embedded systems project built using the **STM32F103C8T6 microcontroller** and RFID technology to identify essential items inside a school bag.

## 📌 Project Overview

SmartBag is designed to help students check whether their required books and other items are packed before leaving. The system uses RFID tags to identify items and provides feedback through an OLED display and buzzer.

## 🛠️ Hardware Components

- STM32F103C8T6 (Blue Pill)
- MFRC522 RFID Reader
- RFID Tags
- SSD1306 OLED Display
- Buzzer
- Connecting Wires

## ✨ Features

- RFID-based item identification
- Scanning of tagged books and items
- Display of scanning information on an OLED screen
- Buzzer indication for missing items

## ⚙️ Working Principle

1. Each book or item is assigned an RFID tag.
2. The RFID reader scans the tags.
3. The STM32 microcontroller processes the scanned information.
4. The OLED display shows the scanning status.
5. The system indicates missing items using a buzzer.

## 💻 Software and Technologies

- Embedded C
- STM32CubeIDE
- STM32CubeMX
- STM32 HAL Libraries

## 🧠 Microcontroller

**STM32F103C8T6 – Blue Pill**

## 📁 Project Structure

- `Core/` – Main application source and header files
- `Drivers/` – STM32 device and peripheral libraries
- `SmartBag.ioc` – STM32CubeMX configuration file
- `STM32F103C8TX_FLASH.ld` – Linker script

## 🚀 Future Improvements

- Add support for more items and RFID tags.
- Improve the user interface.
- Enhance item tracking and notifications.

## 👩‍💻 Project

Developed as an embedded systems project using STM32 and RFID technology.
