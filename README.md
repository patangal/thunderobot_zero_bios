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
This creates a backup of your current BIOS before any modifications.

2. Flash the Unlocked BIOS
# Run as Administrator
flash new bios.bat
3. Extract Current BIOS
# Run as Administrator
pick up current bios.bat
⚠️ Important Safety Information
<div align="center">
Warning

</div>
Risks of BIOS Modification
🔴 Bricking Risk: Incorrect flashing can render your laptop unbootable
🔴 Warranty Void: Modifying BIOS may void manufacturer warranty
🔴 Data Loss: Always backup important data before proceeding
🔴 Power Stability: Ensure stable power supply during flash process
Prerequisites
Laptop fully charged or connected to AC power
Backup of current BIOS created
Understanding of risks involved
Recovery method prepared (programmer/SPI flash tool recommended)
📚 Resources
Original Source
🔗 Chinese Forum Guide & Full Package: Google Drive
Complete documentation (Chinese)
Additional NVIDIA 3060 drivers
Extended tool collection
Compatibility
Spec	Details
Model	ThundeRobot Zero
CPU	11th Gen Intel Core i7
GPU	NVIDIA GeForce RTX 3060
BIOS Type	Insyde H2O
Format	.fd (Firmware Descriptor)
🛠️ Technical Details
Flashing Method
This repository uses Intel Flash Programming Tool (FPTW64) — an official Intel utility for firmware flashing on Intel-based systems.

BIOS Structure
backup.fd: Original firmware dump from OEM system
advanced unlock.fd: Modified firmware with advanced menu unlocked
Both files use standard Intel FD (Flash Descriptor) format
🤝 Contributing
Found an issue or have improvements? Feel free to:

🐛 Open an Issue
📝 Submit a Pull Request
📧 Contact me directly
📧 Support & Contact
<div align="center">
GitHub
Email

</div>
Having problems? Feel free to reach out — I'm happy to help troubleshoot BIOS-related issues.

📜 Disclaimer
<div align="center">
THIS SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.
USE AT YOUR OWN RISK. THE AUTHOR IS NOT RESPONSIBLE FOR ANY DAMAGE
TO YOUR HARDWARE OR DATA RESULTING FROM THE USE OF THESE FILES.
</div>
This is an unofficial modification
Not affiliated with ThundeRobot or Intel
Always verify compatibility with your specific hardware revision
Consider professional assistance if unsure
🙏 Credits
Original Modification: Chinese tech forum community
Tools: Intel Flash Programming Tool (FPTW64)
Guide Translation: Community contributors
<div align="center">
Footer

Made with ⚡ by Patangal Basak

</div> ``` ```
