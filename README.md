<p align="center">
  <img src="https://remio.net/icon-512.png" width="128" height="128" alt="Remio" style="border-radius: 22px;" />
</p>

<h1 align="center">Remio</h1>

<p align="center">
  <strong>Remote desktop for everyone.</strong><br>
  Host on macOS, Windows, Linux, Android, Raspberry Pi & FreeBSD — control from iPhone, iPad, Mac, Android, Windows & Apple TV.
</p>

<p align="center">
  <a href="https://github.com/remioapp/releases/releases"><img src="https://img.shields.io/github/v/release/remioapp/releases?style=flat-square&label=Latest%20Release&color=6C5CE7" alt="Latest Release"></a>
  <a href="https://github.com/remioapp/releases/releases"><img src="https://img.shields.io/github/release-date/remioapp/releases?style=flat-square&label=Updated&color=FF7675" alt="Last Updated"></a>
  <a href="https://github.com/remioapp/releases/releases"><img src="https://img.shields.io/github/downloads/remioapp/releases/total?style=flat-square&label=Downloads&color=00E599" alt="Downloads"></a>
  <a href="https://remio.net"><img src="https://img.shields.io/badge/Website-remio.net-00B4D8?style=flat-square" alt="Website"></a>
</p>

---

## ✨ What is Remio?

Remio is a **native remote desktop** application that lets you access and control your computer from anywhere. Unlike Electron-based alternatives, every Remio app is built from scratch using each platform's native toolkit — delivering **butter-smooth streaming at up to 120FPS — even at 4K** — with minimal latency.

**Hosts — the computer you control:**

- 🖥️ **macOS Host** — Stream your Mac to any device (SwiftUI + ScreenCaptureKit)
- 🪟 **Windows Host** — Stream your Windows PC to any device (C++/WinRT)
- 🐧 **Linux Host** — X11 & Wayland, AppImage/deb/rpm/Arch/Flatpak (C++20)
- 🤖 **Android Host** — Turn a phone or tablet into a computer you can reach (Kotlin + Jetpack Compose)
- 🍓 **Raspberry Pi Host** — Raspberry Pi OS 64-bit & 32-bit builds
- 😈 **FreeBSD Host** — Native FreeBSD 14 package

**Clients — the device you control from:**

- 📱 **iOS & iPadOS Client** — Full multi-touch with Apple Trackpad physics (SwiftUI)
- 💻 **macOS Client** — Native Mac app on the Mac App Store (SwiftUI)
- 🤖 **Android Client** — Native Jetpack Compose experience
- 🪟 **Windows Client** — Native Windows app (C++/WinRT)
- 📺 **Apple TV Client** — Big-screen remote desktop on tvOS (SwiftUI)

## 📥 Download

> 💡 **[remio.net/download](https://remio.net/download) always lists the newest build for every platform** — installers, package-manager files and SHA-256 checksums.

### Host — install on the computer you want to control

| Platform | Download | Requirements |
|----------|----------|--------------|
| **macOS** (Apple Silicon & Intel) | [**⬇️ Download**](https://remio.net/download) · [PKG](https://github.com/remioapp/releases/releases) | macOS 15 Sequoia or later |
| **Windows** (x64) | [**⬇️ Download**](https://remio.net/download) · [EXE](https://github.com/remioapp/releases/releases) | Windows 10 or later |
| **Linux** (x86_64) | [**⬇️ Download**](https://remio.net/download) · AppImage · deb · rpm · Arch · Flatpak | Ubuntu 22.04+, Debian 12+, Fedora 36+, Arch — X11 or Wayland |
| **Android** (phone / tablet) | [**⬇️ Download**](https://remio.net/download) · [APK](https://github.com/remioapp/releases/releases) | Android 14 or later — direct APK, not on Google Play |
| **Raspberry Pi** (arm64 / armhf) | [**⬇️ Download**](https://remio.net/download) · deb · AppImage | Raspberry Pi OS Bookworm or newer (Pi 3/4/5) |
| **FreeBSD** (amd64) | [**⬇️ Download**](https://remio.net/download) · pkg | FreeBSD 14 |

### Client — install on the device you control FROM

| Platform | Download | Status |
|----------|----------|--------|
| **iOS & iPadOS** | [App Store](https://apps.apple.com/app/remio-remote-desktop/id6759306575) | ✅ Available |
| **macOS** | [Mac App Store](https://apps.apple.com/app/remio-remote-desktop/id6759306575) | ✅ Available |
| **Android** | [Google Play](https://play.google.com/store/apps/details?id=com.remio.client) | ✅ Available |
| **Windows** (x64) | [Windows Client installer](https://remio.net/download) | ✅ Available |
| **Apple TV** (tvOS) | [App Store on Apple TV](https://apps.apple.com/app/remio-remote-desktop/id6759306575) | ✅ Available |
| **Apple Vision Pro** | Install the iPad app from the App Store | ✅ Available |
| **Linux** | — | 📋 On Roadmap |

<sub>🗂️ Every installer is also published on the <a href="https://github.com/remioapp/releases/releases">Releases</a> page. Tags are suffixed per platform: <code>-win</code> (Windows Host), <code>-win-client</code> (Windows Client), <code>-linux</code> (Linux &amp; Raspberry Pi), <code>-android</code> (Android Host), <code>-freebsd</code> (FreeBSD); untagged versions are the macOS Host.</sub>

## 🚀 Quick Start

```
1. Download & install Remio Host on your Mac, Windows PC, Linux box, Android device, Pi or FreeBSD server
2. Open Remio on your phone, tablet, TV, or another computer
3. Scan the QR code (or type the six-digit code) — you're connected!
```

That's it. Full desktop streaming in under a minute. No account required.

## ⚡ Key Features

- **100% Native** — SwiftUI on Apple, Jetpack Compose on Android, C++/WinRT on Windows, C++20 on Linux & FreeBSD. Zero Electron.
- **Up to 120FPS** — Silky-smooth 120FPS streaming (4K runs at 120FPS), hardware-accelerated next-gen video compression
- **Ultra-Low Latency** — Sub-16ms on local network
- **End-to-End Encrypted** — Peer-to-peer WebRTC with DTLS-SRTP
- **Multi-Touch** — Natural gesture support with Apple Trackpad physics
- **Keyboard & Mouse** — Full input support including modifier keys
- **Apple Silicon Optimized** — Blazingly fast on M1, M2, M3, M4
- **ProMotion 120Hz** — Buttery smooth on supported devices
- **Zero Config** — QR code pairing, no port forwarding needed

## 🔒 Security & Privacy

- **Peer-to-peer** — Video streams go directly between your devices when possible
- **No data collection** — We don't see, store, or have access to your screen content
- **Open signaling** — Connection setup via lightweight relay, data stays yours
- Read our [Security Whitepaper](https://remio.net/security-whitepaper.html)

## 📋 System Requirements

| Component | Minimum |
|-----------|---------|
| **macOS Host** | macOS 15 Sequoia, Apple Silicon (M1) or Intel |
| **Windows Host** | Windows 10 (x64) |
| **Linux Host** | Ubuntu 22.04+, Debian 12+, Fedora 36+, Arch — X11 or Wayland (x86_64) |
| **Android Host** | Android 14 (API 34)+ — phone or tablet |
| **Raspberry Pi Host** | Raspberry Pi OS Bookworm 64-bit (Pi 3/4/5); 32-bit builds for Pi 2 v1.2+ |
| **FreeBSD Host** | FreeBSD 14 (amd64) |
| **iOS Client** | iOS 18.0+ |
| **iPadOS Client** | iPadOS 18.0+ |
| **macOS Client** | macOS 15 Sequoia or later |
| **Android Client** | Android 12 (API 31)+ |
| **Windows Client** | Windows 10 (x64) |
| **Apple TV Client** | tvOS 18.0+ |

## 📝 Changelog

See the [Releases](https://github.com/remioapp/releases/releases) page for detailed changelogs.

## 🔗 Links

- 🌐 [Website](https://remio.net)
- 📖 [Documentation](https://remio.net/docs.html)
- ❓ [FAQ](https://remio.net/faq.html)
- 🛡️ [Security](https://remio.net/security.html)
- 📧 [Contact](mailto:support@remio.net)

## 📄 License

Remio is proprietary software. See the [Terms of Service](https://remio.net/terms.html) for details.

---

<p align="center">
  Made with ❤️ in Vietnam 🇻🇳 — for remote workers, creators, and gamers everywhere.
</p>
