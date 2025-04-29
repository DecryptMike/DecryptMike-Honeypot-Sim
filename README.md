![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=flat&logo=python&logoColor=white&labelColor=3f3f46)
![Made with](https://img.shields.io/badge/Made%20with-Cryptography-84cc16?style=flat&logo=python&labelColor=3f3f46)
![Simulates](https://img.shields.io/badge/Simulates-Attacks-f97316?style=flat&logo=airplayaudio&labelColor=3f3f46)
![Deception](https://img.shields.io/badge/Deception-Traps-a21caf?style=flat&logo=protonvpn&labelColor=3f3f46)
![Honeypot](https://img.shields.io/badge/Honeypot-Active-ef4444?style=flat&logo=firefox&labelColor=3f3f46)
![Network](https://img.shields.io/badge/Network-Snare-737373?style=flat&logo=protocols&labelColor=3f3f46)
![License](https://img.shields.io/badge/license-MIT-green)

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
