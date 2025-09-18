<div align="center">

# 🎯 Advanced Keylogger System

[![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Windows-green?style=for-the-badge)](https://github.com/Akashr3)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE.md)
[![Author](https://img.shields.io/badge/Author-Akashr3-red?style=for-the-badge)](https://github.com/Akashr3)

*A sophisticated keylogging solution designed for security research and educational purposes*

---

</div>

## 📋 Table of Contents

- [🎯 Overview](#-overview)
- [✨ Features](#-features)
- [🚀 Quick Start](#-quick-start)
- [📁 Project Structure](#-project-structure)
- [⚙️ Configuration](#️-configuration)
- [🛠️ Installation](#️-installation)
- [📖 Usage](#-usage)
- [🔧 Development](#-development)
- [⚠️ Legal Notice](#️-legal-notice)
- [🤝 Contributing](#-contributing)
- [📞 Contact](#-contact)

---

## 🎯 Overview

This project implements a cross-platform keylogging system with advanced features including:

- **Real-time keystroke capture** across Linux and Windows platforms
- **Clipboard monitoring** for comprehensive data collection
- **Telegram integration** for remote data transmission
- **Stealth operation** with background execution
- **Persistence mechanisms** for continuous operation

> **⚠️ IMPORTANT**: This tool is designed exclusively for educational purposes and authorized security testing. Unauthorized use is strictly prohibited.

---

## ✨ Features

### 🔥 Core Capabilities

| Feature | Linux | Windows | Description |
|---------|-------|---------|-------------|
| **Keystroke Logging** | ✅ | ✅ | Captures all keyboard input |
| **Clipboard Monitoring** | ✅ | ✅ | Tracks clipboard changes |
| **Telegram Integration** | ✅ | ✅ | Remote data transmission |
| **Background Operation** | ✅ | ✅ | Stealth execution |
| **Persistence** | ✅ | ⚠️ | Auto-start capabilities |
| **File Hiding** | ❌ | ✅ | Hidden log files |

### 🎨 Advanced Features

- **🔄 Jitter-based timing** to avoid detection patterns
- **📱 Cross-platform compatibility** (Linux/Windows)
- **🔐 Encrypted communication** via Telegram API
- **📊 Structured logging** with timestamps
- **🛡️ Error handling** with remote notifications

---

## 🚀 Quick Start

### Prerequisites

- Python 3.8 or higher
- pip package manager
- Telegram Bot Token (for remote features)

### One-Line Setup

```bash
git clone https://github.com/Akashr3/keylogger.git && cd keylogger
```

---

## 📁 Project Structure

```
keylogger/
├── 📄 README.md                 # Project documentation
├── 📄 LICENSE.md               # MIT License
├── 🐧 Linux/                   # Linux implementation
│   ├── keylogger.py           # Main Linux keylogger
│   ├── README.md              # Linux-specific docs
│   └── requirements.txt       # Python dependencies
└── 🪟 Windows/                 # Windows implementation
    ├── keylogger.py           # Main Windows keylogger
    ├── README.md              # Windows-specific docs
    └── requirements.txt       # Python dependencies
```

---

## ⚙️ Configuration

### Required Settings

Before running the keylogger, configure these essential parameters:

```python
# Telegram Configuration
TOKEN = 'YOUR_TELEGRAM_BOT_TOKEN'    # Get from @BotFather
CHAT_ID = 'YOUR_TELEGRAM_CHAT_ID'    # Your Telegram chat ID
INTERVAL = 120                       # Upload interval (seconds)
```

### 🔧 Configuration Guide

1. **Create Telegram Bot**:
   - Message [@BotFather](https://t.me/BotFather) on Telegram
   - Use `/newbot` command to create a new bot
   - Copy the provided token

2. **Get Chat ID**:
   - Message your bot
   - Visit: `https://api.telegram.org/bot<YOUR_BOT_TOKEN>/getUpdates`
   - Find your chat ID in the response

---

## 🛠️ Installation

### Linux Installation

```bash
cd Linux/
pip install -r requirements.txt
python3 keylogger.py
```

### Windows Installation

```powershell
cd Windows/
pip install -r requirements.txt
python keylogger.py
```

### Create Executable

```bash
# Linux
pyinstaller --noconsole --onefile keylogger.py

# Windows
pyinstaller --noconsole --onefile keylogger.py
```

---

## 📖 Usage

### Basic Operation

1. **Configure** your Telegram credentials
2. **Run** the keylogger script
3. **Monitor** data via Telegram messages
4. **Stop** using Ctrl+C

### Advanced Usage

```bash
# Run with custom interval
python3 keylogger.py --interval 300

# Run in background (Linux)
nohup python3 keylogger.py &

# Run as service (Windows)
pythonw keylogger.py
```

---

## 🔧 Development

### Development Setup

```bash
# Clone repository
git clone https://github.com/Akashr3/keylogger.git
cd keylogger

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
# or
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt
```

### Code Structure

- **`keylogger.py`**: Main keylogging logic
- **`uploader.py`**: Telegram integration
- **`persistence.py`**: Auto-start mechanisms
- **`utils.py`**: Helper functions

---

## ⚠️ Legal Notice

### 🚨 Important Disclaimers

- **Educational Use Only**: This software is intended solely for educational and research purposes
- **Authorized Testing**: Only use on systems you own or have explicit permission to test
- **No Malicious Use**: Any unauthorized use is strictly prohibited
- **Compliance**: Users must comply with all applicable laws and regulations

### 📜 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### 🎯 Ways to Contribute

- 🐛 **Report Bugs**: Found an issue? Let us know!
- 💡 **Suggest Features**: Have ideas? We'd love to hear them!
- 🔧 **Submit Pull Requests**: Fix bugs or add features
- 📖 **Improve Documentation**: Help others understand the project
- ⭐ **Star the Repository**: Show your support!

### 🚀 Getting Started

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

---

## 📞 Contact

<div align="center">

### 👨‍💻 Akash

[![GitHub](https://img.shields.io/badge/GitHub-Akashr3-black?style=for-the-badge&logo=github)](https://github.com/Akashr3)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-blue?style=for-the-badge&logo=gmail)](mailto:akash.ranganath03@gmail.com)

---


**⭐ If you found this project helpful, please give it a star! ⭐**

</div>
