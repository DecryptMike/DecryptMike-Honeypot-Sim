![DecryptMike Honeypot Sim](https://github.com/user-attachments/assets/9310aef4-133b-4604-8493-d2924a4e62af)![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Last Commit](https://img.shields.io/github/last-commit/DecryptMike/DecryptMike-Password-Manager)
![License](https://img.shields.io/badge/license-MIT-green)
![Made With](https://img.shields.io/badge/Made%20with-Cryptography-green?logo=python)
![🧠 Simulates](https://img.shields.io/badge/🧠-Simulates-grey?style=flat-square)
![🎯 Attacks](https://img.shields.io/badge/🎯-Attacks-orange?style=flat-square)
![🎭 Deception](https://img.shields.io/badge/🎭-Deception-purple?style=flat-square)
![🪤 Honeypot](https://img.shields.io/badge/🪤-Honeypot-brown?style=flat-square)
![🚨 Active](https://img.shields.io/badge/🚨-Active-red?style=flat-square)
![🕸️ Network](https://img.shields.io/badge/🕸️-Network-grey?style=flat-square)

<p align="center">
  <img src="DecryptMikeLogo.png" alt="DecryptMike Logo" style="max-width: 100%; height: auto;"/>
</p>

<h3 align="center">
  🕵️‍♂️ Honeypot Simulation Environment
</h3>

<h5 align="center">
   A cyberpunk-inspired honeypot environment designed <br> to simulate common network attacks and log intruder behavior for analysis.
</h5>

---

## 🧠 Overview

This honeypot simulates fake services (SSH, FTP, HTTP) to attract and monitor malicious activity in a controlled environment. It logs all interaction attempts to `logs/honeypot.log`, helping defenders analyze intrusion patterns and improve defense.

---

## 🛠️ Features

- 🔐 **Fake SSH, FTP, and HTTP services**
- 📜 **Real-time attack logging**
- 🎨 **Matrix-style terminal alerts (with Colorama)**
- 💾 **Persistent log output to `logs/honeypot.log`**
- 🔧 **Modular architecture (alerts, logger, services)**

---

## 📸 Screenshot

<p align="center">
  <img src="DecryptMike Honeypot Sim.png" width="100%" alt="Sign In Page">
</p>

---

## 🧪 Sample Output

```
[*] Honeypot is starting...

[!] ALERT - SSH-Attempt from 192.168.1.50: Unauthorized SSH login attempt  
[!] ALERT - FTP-Attempt from 192.168.1.50: Anonymous FTP login attempted  
[!] ALERT - HTTP-Probe from 192.168.1.50: Suspicious HTTP request received
```

---

## 📁 Folder Structure

```
honeypot-sim/
├── honeypot/
│   ├── __init__.py
│   ├── alerts.py
│   ├── fake_services.py
│   ├── logger.py
│   └── logs/
│       └── honeypot.log
├── run.py
├── README.md
├── requirements.txt
```

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/yourusername/honeypot-sim.git
cd honeypot-sim

# (Optional) Set up a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the honeypot
python run.py
```

---

## 🧰 Tech Stack

| Layer       | Tech Used                          |
|-------------|------------------------------------|
| Backend     | Python 3.11, Flask (optional)      |
| Logging     | Colorama, Python Logging           |
| Simulation  | Modular fake service definitions   |
| UI Theme    | SynthWave '84 + Glow               |

---

## 📄 Why I Built It

This project showcases my ability to design and simulate deception techniques used in real-world cybersecurity. By logging attacker behavior against fake services, it highlights my hands-on skills in network defense, monitoring, and threat analysis—all without risking real infrastructure.

---

## ⚠️ Legal Disclaimer

This tool is intended for **educational and authorized personal use only**.  
Do not use it to store sensitive or production passwords without enhancements.

---

## 💻 Built by [@DecryptMike](https://github.com/DecryptMike)

---

<p align="center">
  <img src="https://img.shields.io/badge/Built%20for-Cybersecurity-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Made%20By-DecryptMike-limegreen?style=for-the-badge&logo=github"/>
</p>
