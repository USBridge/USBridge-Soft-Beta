# USBridge Soft

**USBridge Soft** is a universal software client designed to unify the management of physical USBridge KVM hardware and software-based remote nodes within a single interface. I am engineering this solution as a central hub for administrators, enabling seamless transitions between low-level hardware access (BIOS/Boot level) and high-performance OS-level remote management.

## Core Concept

The project is built on a **hybrid approach** to remote infrastructure management:

* **Hardware Mode:** Full "bare-metal" control via USBridge physical KVM-over-IP bridges. This allows for BIOS configuration, OS installation, and recovery tasks.
* **Software Mode:** High-speed remote desktop control via a software agent (similar to TeamViewer). This is optimized for day-to-day administration of running operating systems without requiring additional hardware.

## Key Features

I am developing this client to eliminate tool sprawl. By consolidating hardware and software access into a single application, USBridge Soft provides:

* **Unified Dashboard:** A single pane of glass to monitor and connect to all assets—whether they are physical USBridge hardware units or servers running the software agent.
* **Integrated Networking:** Automatic provisioning of secure P2P tunnels using **Tailscale/WireGuard**. This ensures reliable, encrypted access to any node globally without complex firewall configurations.
* **Adaptive Streaming:** The engine automatically selects the most efficient video protocol based on the connection type—utilizing hardware-accelerated capture for physical bridges or high-framerate screen sharing for software nodes.

## Vision

This evolution transforms USBridge from a collection of standalone devices into a comprehensive **Remote Management Ecosystem**, capable of scaling from a single server to complex, distributed infrastructures.
