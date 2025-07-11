# Simulation-and-Detection-of-WannaCry-Worm-Ransomware-via-SMB-Propagation
This project focuses on simulating and detecting the WannaCry ransomware worm, which propagates through the Server Message Block (SMB) protocol. The WannaCry ransomware, infamous for its global cyberattack in May 2017, exploits vulnerabilities in Microsoft Windows systems, particularly using the EternalBlue exploit to spread across networks. This repository provides tools and scripts to simulate WannaCry's behavior in a controlled environment and implement detection mechanisms to identify and mitigate such threats.

## Features
- **Ransomware Simulation**: Simulates WannaCry's file encryption and ransom note generation to understand its impact in a safe, controlled setting.
- **SMB Propagation**: Demonstrates how WannaCry exploits SMB vulnerabilities to propagate across networks, mimicking its worm-like behavior.
- **Detection System**: Includes scripts to monitor and detect suspicious activities related to WannaCry, such as unauthorized file encryption and network traffic anomalies.
- **Educational Purpose**: Designed for security researchers, blue teams, and red teams to study ransomware behavior, test defenses, and improve cybersecurity measures.

## Architecture
![Infrastructure Architecture](https://github.com/taihieunguyen/Simulation-and-Detection-of-WannaCry-Worm-Ransomware-via-SMB-Propagation/blob/main/Architecture.png?raw=true)

## Project Structure

- **./Source code/WannaCry/**: Contains scripts to simulate WannaCry's encryption and SMB propagation, Includes tools for monitoring and detecting WannaCry-like activities.
- **./report/**: Documentation on WannaCry's mechanics, including EternalBlue exploit and SMB protocol vulnerabilities.

## Requirements
- **Python 3.12.**
- **Libraries: cryptography, watchdog, smbprotocol,..**
- **Virtualized environment (e.g., VMware, VirtualBox) for safe testing.**
- **Windows system for accurate simulation (preferably unpatched for EternalBlue vulnerability).**
---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

---
