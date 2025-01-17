# Multithreaded Port Scanner


## Description

The **Multithreaded Port Scanner** is a simple yet powerful tool for scanning open ports on a target IP address. Leveraging multithreading, this scanner significantly reduces the time needed to perform comprehensive scans. It's suitable for network administrators and cybersecurity enthusiasts to identify open ports and assess network security.

---

## Features
- **Multithreading**: Speeds up scanning by utilizing multiple threads.
- **Multiple Scanning Modes**:
  1. Scans the first 1024 ports (common ports).
  2. Scans up to 49,151 ports (extended range).
  3. Scans a predefined list of common ports.
  4. Allows users to input custom ports.
- **Real-time Output**: Displays open ports as they are discovered.
- **Customizable Thread Count**: Adjust the number of threads for optimal performance.

---

## Requirements

- **Python 3.x**  
- Standard Python libraries:
  - `socket`
  - `queue`
  - `threading`

---

