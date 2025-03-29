# Schedule 1 Save Editor

![Banner](https://github.com/user-attachments/assets/55a8e085-f339-49cb-8ea6-31a5945d4095)

![Python](https://img.shields.io/badge/python-3.9%2B-blue)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey)
![Version](https://img.shields.io/badge/version-1.0.2-green)

## Overview
The **Schedule I Save File Editor** is a graphical user interface (GUI) tool designed to modify save files for the game "Schedule I." Built with PySide6, it features:

- Dark theme interface with tabbed navigation
- Advanced game data modification capabilities
- Built-in backup system with version control
- NPC relationship management tools
- Safe editing workflow with automatic backups

## Features

### 💰 Financial Editing
- Adjust cash balance
- Modify online money
- Set net worth
- Edit lifetime earnings
- Configure weekly deposit sum

### 🏆 Progression Management
- Change organization name
- Modify rank (Street to Kingpin)
- Adjust rank number and tier
- Complete all quests and objectives

### 🏡 Property & Business Control
- Bulk edit property contents
- Unlock all properties
- Manage businesses
- Generate new save files

### 🧪 Product Management
- Discover/undiscover products
- Generate custom products
- Set product prices
- Manage mix recipes

### 🤝 NPC Relationships
- Import NPCs from game logs
- Unlock all NPC relationships
- Recruit all dealers

### 🔄 Advanced Features
- Variable modification
- Achievement unlocker mod installation
- Comprehensive backup system
- Automatic save file detection

## ⚠️ Security Notes

### Antivirus Considerations
Some security solutions may flag the `.exe` version due to:
- PyInstaller packaging
- Memory editing capabilities
- Unusual file operations

| Security Aspect       | Recommendation                |
|-----------------------|-------------------------------|
| False Positives       | Whitelist in antivirus        |
| Source Verification   | Review code on GitHub         |
| Safe Alternative      | Use Python version directly   |

### Verification Steps
1. Check [VirusTotal analysis](https://www.virustotal.com/)
2. Compare hashes with GitHub release
3. Inspect source code integrity

## 🚀 Getting Started

### Requirements
- Python 3.9+
- PySide6 library

### Installation
```bash
# Clone repository
git clone https://github.com/N0edL/Schedule-1-Save-Editor.git
cd Schedule-1-Save-Editor

# Install dependencies
pip install PySide6

# Launch editor
python main.py
