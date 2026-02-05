criado por - baitedbolota
use por sua conta e risco
baixe os requirements e aproveite <3

© 2026 baitedbolota — Licensed under MIT.

# Discord Server Cloner Selfbot

A selfbot designed to clone Discord servers with channels, roles, and settings.

⚠️ Warning: This project violates Discord Terms of Service. Use at your own risk.

---

## 📖 How to Use

### 1. Start the Selfbot

python selfbot_cloner.py

Expected output:

Discord Server Cloner 2.0.0-SELFBOT  
SELFBOT - Violates Discord Terms of Service  
Use at your own risk  
Connected as YourName#1234  
Servers: 5

---

### 2. Get Server IDs

Enable Developer Mode  
Discord > Settings > Advanced  
Enable Developer Mode

Copy ID  
Right-click the server  
Click Copy ID

Or use:

!cloneservers

---

### 3. Clone Server

!clone SOURCE_ID DESTINATION_ID

Example:

!clone 123456789012345678 987654321098765432

---

## 🎮 Commands

!clonehelp / !cloneh  
Shows command list

!cloneservers / !clones  
Lists your servers with IDs

!cloneconfig / !clonec  
Shows current configuration

!clone <source> <destination>  
Clones a server

---

## ⚙️ Configuration

Edit config.json

Basic Settings

token = Your user token  
prefix = Command prefix (!clone)  
debug = Detailed logs

Clone Settings

name_syntax = %original%-copy  
clone_delay = 0.5 seconds recommended  
clear_guild = Clear destination server

---

## 👤 Author

Developed by baitedbolota  
Discord: baitedbolota

---

## 📄 License

MIT License

