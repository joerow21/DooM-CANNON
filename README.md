<p align="center">
  <img src="https://i.postimg.cc/j2Rx23zp/doom-cannon.jpg" width="600"/>
</p>

<h1 align="center"> DOOM CANNON DDoS Tool</h1>

<p align="center">
  🚀 Powered by <b> BANGLADESH CYBER SQUARE and TEAM SHADOW STRIKER </b><br>
  📆 Year: 2025
</p>


---

## 📖 Overview
**DOOM CANNON** is a hybrid CLI toolkit built with **Python** 🐍 and **Go** 🌀.  
It provides a centralized menu system (Python Rich + PyFiglet) to launch multiple Go-powered modules.  
Each module has customizable options (target, port, threads, duration, proxy, headers, etc.).  

⚠️ **Disclaimer**: This tool is for **educational and research purposes only**.  
The authors take no responsibility for misuse.  

---

## ✨ Features
- Interactive CLI with styled menus
- Python-based launcher with Rich UI
- Multiple Go-based modules for different modes
- Custom input support (target, threads, proxy, headers, wordlists)
- Modular structure – easy to add new Go tools

---

## 🛠️ Installation
```bash
pkg update && pkg upgrade
pkg install coreutils -y
pkg install grep -y 
pkg install awk -y
pkg install python -y
pkg install python3 -y
pkg install golang -y
pkg install git 
git clone https://github.com/TEAMBCS/DooM-CANNON.git
cd DooM-CANNON
chmod 777 *
chmod +x *
pip3 install -r requirements.txt
````

---

## ▶️ Usage
   *PYTHON language  launcher*
```bash
python3 DooM_CANNON.py
```
   *GO language launcher*
```bash
go run DooM_CANNON.go
```
   *SHELL language launcher*
```bash
bash DooM_CANNON.sh
```    
You will see a CLI menu with available modules.
Select an option (e.g., `01/A` for ORBIT Attack) and follow the prompts.

---

## 🌳 Project Structure (Detailed Tree)

```
doom-cannon/
│
├── DooM_CANNON.py               # Main Python language  launcher (menu, UI, input handling)
├── DooM_CANNON.go  							#  Go language launcher (menu, UI, input handling)
├── DooM_CANNON.sh 							#  Shell language launcher (menu, UI, input handling)
│
├── orbit.go                 # Orbit Attack (TLS-based)
│   ├─ Inputs: host, port, method [GET/POST], threads, duration, debug, proxy, header
│
├── axis.go                  # Axis Attack (TLS-based)
│   ├─ Inputs: url, port, method [GET/POST], threads, duration, debug, proxy
│
├── viod.go                  # Viod Attack
│   ├─ Inputs: url, port, threads, method, duration, proxy, wordlist, header
│
├── noise.go                 # Noise Attack
│   ├─ Inputs: url, threads, method, duration, proxy, header
│
├── ghost.go                 # Ghost Attack
│   ├─ Inputs: url, port, threads, method, duration, proxy, wordlist
│
├── xiron.go                 # Xiron Attack
│   ├─ Inputs: url, threads, method, duration, proxy
│
├── orix.go                  # Orix Attack
│   ├─ Inputs: url, port, threads, method, duration, proxy
│
├── orrin.go                 # Orrin Attack
│   ├─ Inputs: site, safe_mode [y/n]
│
├── viont.go                 # Viont Attack (Flood mode)
│   ├─ Inputs: url, port, threads, method, duration, header
│
│
├── proxy.txt                # Optional proxy list
├── header.txt               # Optional custom headers
└── wordlist                 # Optional wordlist for specific modules
```

---
## DOOM CANNON UI 
<p align="center">
  <img src="https://i.postimg.cc/sg05WqgC/doom-ui.jpg" width="600"/>
