#  Recon Scanner

**CLI-based Website Reconnaissance & Vulnerability Scanner**.
A powerful Python tool to perform automated reconnaissance and identify security misconfigurations.
Recon Scanner is an automated cybersecurity reconnaissance tool that collects essential target information such as open ports, DNS records, WHOIS details, HTTP headers, and webpage metadata. It is designed to assist in footprinting and enumeration phases of security testing with a clean and easy-to-use CLI interface.

---

##  Features

*  Domain & WHOIS Information
*  DNS Enumeration
*  SSL/TLS Certificate Analysis
*  HTTP Headers Inspection
*  Network Port Scanning 
*  Vulnerability Detection Engine
*  Severity-based Risk Classification
*  Professional PDF Report Generation

---

##  Installation

###  Install via pip (Recommended)

```bash
pip install recon-scanner
```

---

###  Install from GitHub

```bash
git clone https://github.com/AvirajShinde/recon-scanner.git
cd recon-scanner
pip install .
```

---

##  Usage

###  Run the tool

```bash
recon-scanner example.com
```

OR (if interactive mode is enabled):

```bash
recon-scanner
```

---

##  Output

*  Reports are saved in: `/reports`
*  Logs are saved in: `/logs`

---

##  Technologies Used

* Python 3
* Nmap
* Requests
* BeautifulSoup
* DNSPython
* ReportLab

---

##  Disclaimer

This tool is intended for:

*  Educational purposes
*  Authorized security testing

 Do NOT use this tool on systems without proper permission.
Unauthorized scanning may be illegal.

---

##  Author

**Aviraj Shinde**
Cyber Security Analyst

---

##  Contribute

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Submit a Pull Request

---

##  License

This project is licensed under the MIT License.

---

##  Future Improvements

* CVSS scoring integration
* Web-based dashboard
* API-based scanning
* Docker support
* Multi-target scanning

---
