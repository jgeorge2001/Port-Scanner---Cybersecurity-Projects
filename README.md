# Port-Scanner---Cybersecurity-Projects
Created a port scanner using python and nmap to examine open ports.


This project leverages `nmap` to scan and gather information about network hosts. The scan options include service version detection and running NSE scripts for basic checks.

## Features
- **Port Scanning**: Identify open ports on a target machine.
- **Service Version Detection**: Detect the version of services running on open ports.
- **Host Discovery**: Display the hostnames and state (up/down) of scanned machines.
- **Protocol Discovery**: Identify which protocols are in use (e.g., TCP, UDP).
- **NSE Script Execution**: Run built-in nmap scripts for additional insights.

## Prerequisites
- Python 3.x
- `nmap` installed on the system
- `python-nmap` library

### Install the `python-nmap` package:

```bash
pip install python-nmap
