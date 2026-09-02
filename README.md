# 🚀 NeXDM — High-Performance 64-Segment Download Manager for Windows

[![Download NeXDM](https://img.shields.io/badge/Download-NeXDM%20for%20Windows-00E5FF?style=for-the-badge&logo=windows&logoColor=white)](https://nexdm.in)
[![VirusTotal Clean](https://img.shields.io/badge/VirusTotal-0%2F70%20Clean-39FF14?style=for-the-badge&logo=shield)](https://www.virustotal.com/gui/file/65e898863615f86c52ed2fc788ae420fab929799f47b7b0721ffa0257d6db908)
[![License](https://img.shields.io/badge/License-MIT%20Freeware-blue?style=for-the-badge)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011%20(x64)-informational?style=for-the-badge&logo=windows)](https://nexdm.in)

> **NeXDM** is an ultra-fast, lightweight desktop download accelerator, BitTorrent engine, and media stream extractor built with native Rust for modern Windows systems.

---

## ✨ Key Features

- **⚡ 64-Connection Turbo Engine:** Splits downloads into up to 64 concurrent segments with dynamic TCP window scaling for maximum bandwidth utilization.
- **🧲 Native BitTorrent Engine:** Paste torrent files and magnet links directly into NeXDM without requiring heavy external P2P clients.
- **🚀 Wi-Fi + 5G Speed Bonding:** Bind multiple network interfaces (Wi-Fi + USB 5G Tethering) simultaneously for 2X download throughput.
- **🔄 Smart Pause & Resume:** Resilient connection recovery with automated retry logic for interrupted downloads.
- **🌐 Native Browser Integration:** Companion browser bridge for seamless one-click download capture from Chrome, Edge, Brave, and Firefox.
- **🛡️ 100% Free & Safe:** Free community software without adware, background telemetry, or bundled junk.

---

## 📥 Download & Installation

### Option 1: Direct Installer
* **Official Website:** [https://nexdm.in](https://nexdm.in)
* **Latest GitHub Releases:** [GitHub Releases Page](https://github.com/nexdm2026/NexDM-Releases/releases/latest)

### Option 2: Windows Package Manager (Winget)
```powershell
winget install NexDM.NexDM
```

### System Requirements:
* **OS:** Windows 10 (64-bit) / Windows 11 (64-bit)
* **Architecture:** x86_64
* **RAM:** 2 GB Minimum (4 GB Recommended)
* **Installer Size:** 5.0 MB (Ultra-Lightweight)

---

## 🔏 Cryptographic Verification (v1.1.4)

Every official release binary is cryptographically hashed for complete transparency and tamper-proofing:

| Artifact | Architecture | SHA-256 Checksum |
| :--- | :--- | :--- |
| `NexDM_x64-setup.exe` | Windows x64 (64-bit) | `0DEDEC12ED9EE922FC2C13700B1CFCF26929EB5A8065E4CB2B74CEDB354C00D9` |

To verify the installer integrity on your PC, run in PowerShell:
```powershell
Get-FileHash -Path "NexDM_x64-setup.exe" -Algorithm SHA256
```

---

## 📦 Winget Manifest Repository

The official Windows Package Manager manifest files for Microsoft's `winget-pkgs` repository are maintained under:
```
winget-manifests/manifests/n/NexDM/NexDM/1.1.4/
├── NexDM.NexDM.yaml
├── NexDM.NexDM.installer.yaml
└── NexDM.NexDM.locale.en-US.yaml
```

---

## 📄 License

This distribution is released under the [MIT License](LICENSE).  
Copyright © 2026 NeXDM Engineering. All rights reserved.
