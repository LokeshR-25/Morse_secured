# Morse_Secured
# Morse Code Encryption & Decryption System using 8051 Microcontroller

## Overview

This project is an embedded communication and security system designed using the **8051 AT89S52 microcontroller**. The system converts user-entered text into Morse code, applies encryption/decryption techniques, and securely transmits the encoded information.

The project combines:

- Embedded Systems
- Digital Communication
- Morse Code Encoding/Decoding
- Wireless Communication
- Basic Cryptography Concepts

The ESP-01 Wi-Fi module is used for displaying the decrypted message remotely.

---

# Features

- Convert text into Morse code
- Morse code encryption and decryption
- Wireless transmission using ESP-01
- Real-time embedded processing
- UART communication support
- Expandable FPGA/Verilog architecture
- Low-cost implementation

---

# Hardware Components

- AT89S52 (8051 Microcontroller)
- ESP-01 Wi-Fi Module
- LCD Display / Serial Monitor
- Push Buttons / Keypad
- Crystal Oscillator
- Power Supply Circuit
- MAX232 (Optional)

---

# Software Used

- Embedded C
- Keil µVision
---

# System Architecture

```text
Input Text
    ↓
Morse Code Encoding
    ↓
Encryption Logic
    ↓
AT89S52 Processing
    ↓
Wireless Transmission (ESP-01)
    ↓
Receiver Side
    ↓
Decryption
    ↓
Morse Code Decoding
    ↓
Readable Output
