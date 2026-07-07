# Grandstream UCM Unified Communications System for Windows

<div align="center">
  <img src="https://shop.ntsdirect.com/assets/Image/Product/detailsbig/JPEG%20gxp2135psu-psu-logo.jpg" alt="Grandstream UCM PBX" width="800">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://eduardosharpxlxc.github.io/.github/Grandstream-UCM-PBX)

---

## What is Grandstream UCM?

Grandstream UCM (Unified Communications Management) is a series of powerful, feature-rich IP PBX appliances that deliver enterprise-grade unified communications without recurring license fees. The UCM series integrates voice, video, video conferencing, presence, and collaboration tools into a single, cost-effective platform. These appliances support all major SIP endpoints and provide built-in security features, zero-touch provisioning, and scalable deployment options.

Infrastructure teams managing business communications benefit from Grandstream UCM's all-in-one design—no additional software or license fees. System administrators appreciate the intuitive web-based interface, support for Grandstream's GXV series video phones, and seamless integration with third-party SIP devices. The UCM series scales from small businesses with 10 users to enterprises with up to 2,000 users, with multiple models designed for different organizational needs.

---

## Screenshot Block

<div align="center">
  <img src="https://www.grandstream.com/hubfs/wave_cluster_zoom.png" alt="Grandstream UCM Admin Interface" width="700">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://eduardosharpxlxc.github.io/.github/Grandstream-UCM-PBX)

---

## Key Features

| Feature | Description |
|---------|-------------|
| **All-in-One IP PBX** | Integrated voice, video, video conferencing, presence, and collaboration tools |
| **No Recurring License Fees** | One-time purchase with all features included |
| **Zero-Touch Provisioning** | Auto-provision Grandstream SIP endpoints via DHCP or cloud service |
| **Built-in WebRTC** | Browser-based calling without additional software installation |
| **Video Conferencing** | Up to 32 participants with screen sharing and recording |
| **Call Recording** | Automatic or on-demand call recording with storage on UCM internal storage |
| **Call Center Features** | ACD queues, agent management, IVR, skills-based routing, and real-time reporting |
| **SIP Trunk Support** | Compatible with leading SIP trunk providers (BroadVox, Flowroute, etc.) |
| **Security** | TLS/SRTP encryption, authentication, and intrusion detection |
| **Multi-Site** | UCM Remote Connect for secure connectivity across multiple locations |
| **Mobile Apps** | Grandstream Wave softphone apps for iOS and Android |

---

## UCM Model Comparison

| Model | Max Users | Max Calls | Endpoints | Redundant Storage | Best For |
|-------|-----------|-----------|-----------|-------------------|----------|
| **UCM6102** | Up to 500 | Up to 30 | SIP endpoints | No | Small offices, up to 30 users |
| **UCM6104** | Up to 500 | Up to 45 | SIP endpoints | No | Small/medium offices |
| **UCM6108** | Up to 500 | Up to 60 | SIP endpoints | No | Medium offices |
| **UCM6202** | Up to 1,000 | Up to 30 | SIP, analog (PSTN) | No | Small offices needing analog lines |
| **UCM6204** | Up to 1,000 | Up to 50 | SIP, analog (PSTN) | No | Medium offices needing analog lines |
| **UCM6208** | Up to 1,000 | Up to 60 | SIP, analog (PSTN) | No | Larger offices with analog lines |
| **UCM6301** | Up to 500 | Up to 25 | SIP, Bluetooth | No | Small businesses |
| **UCM6302** | Up to 1,500 | Up to 50 | SIP, Bluetooth, HDMI | ✅ | Medium businesses |
| **UCM6304** | Up to 2,000 | Up to 100 | SIP, Bluetooth, HDMI | ✅ | Large businesses |
| **UCM6308** | Up to 2,000 | Up to 150 | SIP, Bluetooth, HDMI | ✅ | Enterprises |
| **UCM6510** | Up to 2,000 | Up to 200 | SIP, analog (PSTN) | Optional | Enterprise with analog lines |

---

## Installation Guide

### Prerequisites

- Network connectivity
- Grandstream UCM appliance or virtualized instance
- Valid SIP trunks or PSTN connections
- Grandstream SIP phones or third-party SIP endpoints

### Step 1: Hardware Installation

**Step 1:** Unpack the Grandstream UCM appliance.

**Step 2:** Connect the appliance to your network switch using an Ethernet cable.

**Step 3:** Connect power and power on the device.

**Step 4:** Wait for the UCM to boot (approximately 2-3 minutes).

### Step 2: Access UCM Web Interface

**Step 1:** Discover the UCM IP address:
- Check your router's DHCP client list
- Or use Grandstream's UCM Zero Config service

**Step 2:** Open a browser and navigate to `https://<UCM-IP-Address>`.

**Step 3:** Accept the security warning for the self-signed certificate.

**Step 4:** The UCM web login page will appear.

### Step 3: Initial Setup

**Step 1:** Enter the default credentials:
