# 🚀 nmap_auto — Ultimate Nmap Automation Suite

Nmap is the gold standard in network and application reconnaissance.  
**nmap_auto** turns it into a *professional-grade automation tool* for penetration testers, Red Teamers, SOC analysts, and IT security staff.

---

## ⚡️ Features

- **Multiple Scan Profiles:**  
  Choose from quick, full, vuln, web, stealth, or your own custom settings — all with a single command.
- **Parallel Scanning:**  
  Dramatically reduce time on large scopes by scanning multiple hosts at once (you choose the number of threads).
- **Smart Output:**  
  Every scan is timestamped and saved to a structured folder, with a unique file per target/profile.
- **Flexible Targeting:**  
  Scan a single host, or batch-scan hundreds of IPs/domains from a file.
- **Custom Ports:**  
  Speed up scans or focus on specific services by targeting only the ports you want.
- **Advanced Evasion:**  
  Stealth profile leverages Nmap’s most effective firewall/IDS bypass options (fragmentation, MAC spoofing, custom source port, low-and-slow timing).
- **Full Nmap Power:**  
  Built-in support for OS and version detection, NSE scripting, service enumeration, banner grabbing, and more.
- **Expandable:**  
  Pass *any* custom Nmap arguments for cutting-edge or situational scans.

---

## 🛠️ Installation

1. **Clone or download this repository:**
    ```bash
    git clone https://github.com/YOUR_GITHUB/nmap_auto.git
    cd nmap_auto
    ```

2. **Install dependencies (Python 3 and Nmap):**
    ```bash
    sudo apt update
    sudo apt install nmap python3
    ```

3. *(Optional)* Create a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

---

## 🚦 Usage

### **Scan a single host with the "quick" profile**
```bash
sudo python3 nmap_auto.py -t scanme.nmap.org -p quick

### **Scan a single host with the "quick" profile**
```bash
sudo python3 nmap_auto_power.py -t scanme.nmap.org -p quick

