# Penetration-Testing-Toolkit

COMPANY: CODTECH IT SOLUTIONS

NAME: MONICA REMOLA.K

INTERN ID:CT06DF1639

DOMAIN:FRONT END DEVELOPMENT

DURATION:6 WEEKS

MENTOR:NEELA SANTOSH

# Penetration Testing Toolkit

## Overview

The Penetration Testing Toolkit is a modular Python-based toolkit designed to assist security professionals, students, and enthusiasts in performing basic penetration testing tasks. The first module included in this toolkit is a Port Scanner, which allows users to scan a target host for open ports within a specified range. This toolkit is intended for educational and authorized testing purposes only.

## Features

- **Port Scanner Module:**
  - Scans a target IP address or domain for open ports within a user-defined range.
  - Simple command-line interface for ease of use.
  - Fast scanning using Python's built-in socket library.
- **Modular Design:**
  - Easily extendable to include additional penetration testing modules (e.g., brute-forcer, banner grabber).

## Setup Instructions

1. **Prerequisites:**
   - Python 3.x installed on your system.

2. **Download the Script:**
   - Save `port_scanner.py` in your project directory.

3. **(Optional) Create a Virtual Environment:**
   - For best practices, you can create and activate a virtual environment:
     ```
     python -m venv venv
     venv\Scripts\activate  # On Windows
     source venv/bin/activate  # On macOS/Linux
     ```

## Usage Guide

1. Open a terminal and navigate to the directory containing `port_scanner.py`.
2. Run the script:
   ```
   python port_scanner.py
   ```
3. Follow the prompts:
   - Enter the target IP address or domain (e.g., `127.0.0.1` or `scanme.nmap.org`).
   - Enter the start port (e.g., `1`).
   - Enter the end port (e.g., `100`).
4. The script will scan the specified range and display any open ports found.

## Example Output

```
Enter target IP or domain: 127.0.0.1
Enter start port (e.g., 1): 1
Enter end port (e.g., 100): 100
Scanning 127.0.0.1 from port 1 to 100...
Open ports on 127.0.0.1:
  - Port 22
  - Port 80
```

If no open ports are found, you will see:
```
No open ports found on 127.0.0.1 in the range 1-100.
```

## Technical Details

- **Language:** Python 3
- **Libraries:** Uses only Python's built-in `socket` library (no external dependencies required for the port scanner).
- **Cross-Platform:** Works on Windows, macOS, and Linux.
- **Extensibility:** The toolkit is designed to be modular, allowing for easy addition of new penetration testing modules.

## Notes

- Use this toolkit only on systems and networks you have explicit permission to test.
- Unauthorized scanning of networks is illegal and unethical.
- For best results, run the script with administrator/root privileges (some ports may require elevated permissions).


