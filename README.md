#  Recon Scanner

CLI-based Website Reconnaissance & Vulnerability Scanner. A powerful Python tool to perform automated reconnaissance and identify security misconfigurations. Recon Scanner is an automated cybersecurity reconnaissance tool that collects essential target information such as open ports, DNS records, WHOIS details, HTTP headers, and webpage metadata. It is designed to assist in footprinting and enumeration phases of security testing with a clean and easy-to-use CLI interface.

---

##  Features

*  Domain Information
*  DNS Enumeration
*  Open Port Scanning
*  SSL Certificate Details
*  WHOIS Lookup
*  HTTP Headers Analysis
*  Metadata Extraction

---

##  Installation

###  1. Clone the Repository

```bash
git clone https://github.com/AvirajShinde/recon-scanner.git
cd recon-scanner
```

---

###  2. Create Virtual Environment (IMPORTANT)

> Kali Linux blocks global pip installs (PEP 668), so use virtual environment

```bash
python3 -m venv venv
```

---

###  3. Activate Virtual Environment

```bash
source venv/bin/activate
```

You should see:

```bash
(venv) user@kali
```

---

###  4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

##  Usage

```bash
python recon-scanner.py
```

---

##  Troubleshooting

###  Error: externally-managed-environment

 Fix: Use virtual environment (recommended)

---

###  Error: venv not found

```bash
sudo apt install python3-venv -y
```

---

###  Permission issues

Make sure you're not running from read-only directories like `/media/cdrom`

---

##  Requirements

* Python 3.x
* Linux (Kali recommended)
* Internet connection

---

##  Project Structure

```
recon-scanner/
│
├── recon-scanner.py
├── requirements.txt
├── README.md
└── setup.cfg
```

---

##  Author

**Aviraj Shinde**
Cybersecurity | VAPT Enthusiast

---

##  Future Improvements

* GUI support 
* Multi-threaded scanning
* API integration

---

##  Support

If you like this project, give it a ⭐ on GitHub!

---
