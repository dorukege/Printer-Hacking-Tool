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
