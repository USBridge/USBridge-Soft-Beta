# Setup Guide — USBridge Soft Beta
 
## Quick Start
 
### 1. Download
 
Download the **Client** for your platform from the [main page](README.md).
 
Download the **Agent** and install it on the machine you want to control.
 
### 2. Run the Client
 
Unzip the archive and run the executable. No installation required.
 
```
USBridge-Client-win-x64/
└── USBridgeClient.exe   ← run this
```
 
### 3. Connect
 
**Software Mode (agent-based):**
1. Install and run the Agent on the target machine
2. The target machine will appear in your dashboard automatically
3. Click Connect
**Hardware Mode (USBridge KVM device):**
1. Connect the USBridge KVM device to the target machine via USB
2. Connect the device to your network
3. The device appears in your dashboard
4. Click Connect — access BIOS via SSH terminal or use standard video KVM
---
 
## System Requirements
 
**Client:**
| Platform | Requirements |
|----------|-------------|
| Windows | Windows 10 or later, x64 |
| macOS | macOS 12 or later, Apple Silicon or Intel |
| Linux | Ubuntu 20.04+, Debian 11+, x64 |
| Android | Android 8.0 or later |
 
**Agent:**
| Platform | Requirements |
|----------|-------------|
| Windows | Windows 10 or later, x64 |
| macOS | macOS 12 or later |
| Linux | 🚧 In development |
 
---
 
## Known Issues (Beta)
 
- Linux agent is not yet available
- No auto-updater — download new releases manually from GitHub
- Some VPN configurations may affect P2P tunnel establishment
---
 
## Getting Help
 
- 💬 [Join Discord](https://discord.com/invite/xqQ6ybkfWS) — fastest way to get help and get the Beta Tester role
- 🐛 [Report a bug](https://github.com/USBridge/USBridge-Soft/issues/new?template=bug_report.md)
- 💡 [Request a feature](https://github.com/USBridge/USBridge-Soft/issues/new?template=feature_request.md)
