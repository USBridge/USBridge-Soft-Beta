# USBridge Remote (Beta)

![USBridge Remote](assets/banner.png)

<div align="center">

[![Beta](https://img.shields.io/badge/status-beta-orange)](https://github.com/USBridge/USBridge-Remote-Beta/releases)
[![Windows](https://img.shields.io/badge/Windows-0078D6?logo=windows&logoColor=white)](#download)
[![macOS](https://img.shields.io/badge/macOS-000000?logo=apple&logoColor=white)](#download)
[![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)](#download)
[![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white)](#download)
[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?logo=discord&logoColor=white)](https://discord.com/invite/xqQ6ybkfWS)

</div>

---

**USBridge Remote** is a unified high-performance client for managing remote machines. I designed it to combine **hardware-level BIOS access** (via USBridge KVM devices) and **software-based remote desktop** in a single, streamlined interface.

> ⚠️ **Beta Software** — This is an early release. Expect bugs. Please report issues via [GitHub Issues](https://github.com/USBridge/USBridge-Remote-Beta/issues) or join our [Discord](https://discord.com/invite/xqQ6ybkfWS) for support.

---

## Download

### Client
*Run this on the device you are using to control others.*

| | Windows | macOS | Linux | Android |
|:---|:---:|:---:|:---:|:---:|
| **x86_64** | [Download](https://github.com/USBridge/USBridge-Remote-Beta/releases/download/v1.0.0-alpha/USBridgeClient-1.0.0-windows-x86_64.zip) |  | [Download](https://github.com/USBridge/USBridge-Remote-Beta/releases/download/v1.0.0-alpha/USBridgeClient-1.0.0-linux-x86_64.tar.gz) |  |
| **ARM64** |  | [Download](https://github.com/USBridge/USBridge-Remote-Beta/releases/download/v1.0.0-alpha/USBridgeClient-1.0.0-macOS-arm64.zip) |  | [Download](https://github.com/USBridge/USBridge-Remote-Beta/releases/download/v1.0.0-alpha/USBridgeClient-1.0.0-android-arm64.apk) |

### Agent
*Run this on the computer you want to access remotely.*

| | Windows | macOS | Linux |
|:---|:---:|:---:|:---:|
| **x86_64** | [Download](https://github.com/USBridge/USBridge-Remote-Beta/releases/download/v1.0.0-alpha/USBridgeAgent-1.0.0-windows-x86_64.zip) |  | 🚧 |
| **ARM64** |  | [Download](https://github.com/USBridge/USBridge-Remote-Beta/releases/download/v1.0.0-alpha/USBridgeAgent-1.0.0-macOS-arm64.zip) | 🚧 |

---

## Features

![USBridge Remote — Remote Desktop](assets/screenshot_USBridge_client.png)

**One place for everything** — I've unified the workflow. Manage USBridge KVM hardware and software agents from a single dashboard. Add a machine, connect, and you're in.

**No limits, no subscriptions** — Completely free. No session time limits, no connection caps, and no account required on the target machine.

**Low-latency video** — My adaptive streaming engine selects the most efficient protocol based on your connection. Enjoy up to 2K resolution with minimal lag thanks to FFmpeg hardware acceleration (DXGI, AVFoundation, VAAPI).

**Tailscale integration** — Built-in encrypted P2P tunneling. Connect to any machine globally without messing with port forwarding or firewall rules. It works on LAN and over the internet automatically.

![USBridge Remote — Agent](assets/screenshot_USBridge_agent.png)

---

## Community & Beta Testing

Join our Discord to get the **Beta Tester** role, report bugs, and help me shape the roadmap:

**[discord.com/invite/xqQ6ybkfWS](https://discord.com/invite/xqQ6ybkfWS)**

---

## Links

- 🌐 [Official Website](https://usbridge.io)
- 🛒 [USBridge KVM 2.0 on Crowd Supply](https://crowdsupply.com/usbridge-technologies/usbridge-kvm-2-0)
- 💬 [Discord](https://discord.com/invite/xqQ6ybkfWS)
