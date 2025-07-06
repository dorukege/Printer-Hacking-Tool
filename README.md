Disclaimer

This project is for educational use and authorized security testing only.
The author is NOT responsible for any misuse or illegal activity conducted with this tool.
Use responsibly and only test devices you own or have explicit permission to test.

# Printer-Hacking-Tool
Interactive Python toolkit for printer security testing, including Nmap scans, SNMP queries, raw message sending

# Printer Pentest Toolkit

A simple Python-based interactive toolkit to scan and test network printers.  
Designed for educational and authorized penetration testing purposes only.

## Features

- Nmap scan on common printer ports (1-10000)  
- SNMP walk (community: public)  
- Send raw messages to printer port 9100  
- Launch PRET tool if installed

## Requirements

- Python 3  
- `nmap` command-line tool installed and available in PATH  
- `snmpwalk` installed and available in PATH  
- Optional: PRET tool ([https://github.com/RUB-NDS/PRET](https://github.com/RUB-NDS/PRET))

## Usage

```bash
python3 printer_pentest.py
```



## Prerequisites

Before running the Printer Pentest Toolkit, ensure you have the following installed and configured on your system:

1. **Python 3**  
   Download and install from [https://www.python.org/downloads/](https://www.python.org/downloads/).

2. **Nmap**  
   - **Linux (Debian/Ubuntu):**  
     ```bash
     sudo apt install nmap
     ```  
   - **macOS (with Homebrew):**  
     ```bash
     brew install nmap
     ```  
   - **Windows:**  
     Download and install from [https://nmap.org/download.html](https://nmap.org/download.html), and ensure `nmap.exe` is added to your system PATH.

3. **snmpwalk (Net-SNMP)**  
   - **Linux (Debian/Ubuntu):**  
     ```bash
     sudo apt install snmp
     ```  
   - **macOS (with Homebrew):**  
     ```bash
     brew install net-snmp
     ```  
   - **Windows:**  
     Download and install from [http://www.net-snmp.org/](http://www.net-snmp.org/) and add the binaries to your PATH.

4. **Python module `python-nmap` (optional, for extended features)**  
   ```bash
   pip install python-nmap




