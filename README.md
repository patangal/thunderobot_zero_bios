```markdown
<div align="center">

![ThundeRobot](https://img.shields.io/badge/ThundeRobot-Zero-FF6B00?style=for-the-badge&logo=thunder&logoColor=white)
![BIOS](https://img.shields.io/badge/BIOS-Backup%20%26%20Unlock-00D26A?style=for-the-badge)
![Platform](https://img.shields.io/badge/Intel-11th%20Gen%20i7-0071C5?style=for-the-badge&logo=intel&logoColor=white)
![GPU](https://img.shields.io/badge/NVIDIA-RTX%203060-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

# ⚡ ThundeRobot Zero BIOS Repository

**Original OEM BIOS & Unlocked Advanced BIOS for 11th Gen i7 + RTX 3060**

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Stable-brightgreen.svg)]()
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2024-blue.svg)]()

</div>

---

## 📋 Overview

This repository contains BIOS firmware files for the **ThundeRobot Zero gaming laptop** (11th Gen Intel i7 + NVIDIA RTX 3060 configuration), including:

- ✅ **Original OEM BIOS backup** — Factory default settings
- 🔓 **Unlocked Advanced BIOS** — Full feature access including Optimus toggle
- 🛠️ **Flashing tools & scripts** — Easy backup and flash utilities

> ⚠️ **WARNING**: BIOS modification carries inherent risks. Proceed with caution and at your own risk.

---

## 📁 Repository Contents

| File | Description | Purpose |
|------|-------------|---------|
| `backup.fd` | Original OEM BIOS | Factory default firmware backup |
| `advanced unlock(i7+3060).fd` | Unlocked BIOS | Modified firmware with advanced features enabled |
| `FPTW64.exe` | Intel Flash Programming Tool | Official BIOS flasher utility |
| `flash backup bios.bat` | Backup Script | Creates backup of current BIOS |
| `flash new bios.bat` | Flash Script | Flashes the unlocked/modified BIOS |
| `pick up current bios.bat` | Read Script | Extracts current BIOS from system |

---

## 🚀 Key Features (Unlocked BIOS)

The modified BIOS unlocks several advanced features not available in the stock firmware:

| Feature | Status | Description |
|---------|--------|-------------|
| 🔧 **Optimus Toggle** | ✅ Enabled | Manually enable/disable NVIDIA Optimus |
| 🎮 **GPU Switching** | ✅ Unlocked | Direct control over dGPU/iGPU configuration |
| ⚙️ **Advanced Settings** | ✅ Exposed | Full access to hidden BIOS options |
| 🌡️ **Thermal Controls** | ✅ Enhanced | Advanced fan and thermal management |
| 📊 **Power Management** | ✅ Unlocked | Customizable power limits and profiles |

> 📌 **Note**: Complete feature list available in the original Chinese forum guide (see [Resources](#-resources)).

---

## ⚡ Quick Start

### 1. Backup Your Current BIOS (Recommended)

```batch
# Run as Administrator
flash backup bios.bat
