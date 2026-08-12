# Quantum-Resistant-cyber-security-apparatus
A cybersecurity prototype designed to explore quantum-resistant security techniques for protecting sensitive data from future quantum computing threats.
# Quantum-Resistant Cyber Security Apparatus

## Project Status
🚧 Phase 1 Completed – Project Under Development

## Overview
The Quantum-Resistant Cyber Security Apparatus is a portable cybersecurity prototype designed to provide a dual-layer security mechanism using encryption and image steganography.

The proposed system combines SM4 encryption in CBC mode with Least Significant Bit (LSB) image steganography. The encrypted data is hidden inside a carrier image, providing both data confidentiality and covert communication.

The system is designed to run on a Raspberry Pi 4 and provides a Flask-based web interface for user interaction.

## Objectives
- Develop a secure data protection system using SM4 encryption.
- Hide encrypted data using LSB image steganography.
- Implement encryption and decryption with IV management.
- Deploy the system on Raspberry Pi 4.
- Provide a simple Flask web interface.
- Perform integrity checking using CRC/HMAC.
- Display system status using a 16×2 LCD.
- Maintain operation logs using SQLite.

## Key Features
- 🔐 SM4 encryption
- 🖼️ LSB image steganography
- 🛡️ Data integrity verification
- 🍓 Raspberry Pi 4 based implementation
- 🌐 Flask web interface
- 📊 SQLite logging
- 📟 16×2 LCD status display
- 💻 Offline and portable operation

## System Workflow

1. User uploads a carrier image.
2. User provides secret text or image data.
3. The secret data is encrypted.
4. The encrypted data is converted into a binary payload.
5. The payload is embedded into the carrier image using LSB steganography.
6. The resulting stego-image can be extracted later.
7. The extracted data is verified and decrypted using the appropriate key.

## Hardware Requirements
- Raspberry Pi 4
- MicroSD Card
- 5V Power Supply
- 16×2 LCD Display
- Network connectivity
- Keyboard and mouse for initial setup
- HDMI monitor for development (optional)

## Software Requirements
- Raspberry Pi OS
- Python 3
- Flask
- SQLite
- Pillow
- NumPy
- SM4 cryptography implementation
- HTML
- CSS
- JavaScript

## System Architecture

The system consists of the following major components:

- User Web Interface
- Flask Web Server
- SM4 Encryption/Decryption Module
- Pillow/NumPy Image Processing Layer
- LSB Steganography Engine
- Local File System
- SQLite Database
- Raspberry Pi OS

## Project Documentation

The Phase 1 documentation contains:

- Introduction
- Literature Survey
- Requirement Specification
- System Design
- Software Components
- System Architecture
- Data Flow Diagram
- Class Diagram
- Sequence Diagram

## Current Progress

### Phase 1
- [x] Problem identification
- [x] Objectives defined
- [x] Literature survey
- [x] Requirement specification
- [x] Hardware and software requirements
- [x] System design
- [x] System architecture
- [x] Data flow design
- [x] Class diagram
- [x] Sequence diagram

### Phase 2
- [ ] Hardware implementation
- [ ] SM4 implementation
- [ ] LSB steganography implementation
- [ ] Flask web interface
- [ ] SQLite logging
- [ ] System integration
- [ ] Testing and validation
- [ ] Final results

## Future Enhancements
- Improved security mechanisms
- Hardware-level security enhancements
- Real-time threat detection
- Improved secure communication
- Further optimization for Raspberry Pi

## Team Project
Quantum-Resistant Cyber Security Apparatus  
Academic Year: 2026–27
