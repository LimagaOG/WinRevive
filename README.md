# RL-WinRevive 🚀
*An ultra-lightweight, native C++ system optimization utility by **Riswan-Limaga Enterprises**.*

---

## 📌 The Problem
Modern operating systems like Windows 11 introduce heavy architectural overhead, including aggressive background telemetry, update orchestrators, and virtualized security features (VBS). On aging hardware—especially mechanical 5400RPM hard drives and limited RAM configurations—these background processes constantly hammer the disk read-heads, creating severe input lag and high idle resource consumption.

## 🛠️ The Solution: RL-WinRevive
**RL-WinRevive** is a lightning-fast, zero-dependency native C++ executable designed to surgically strip away Windows 11 bloat without breaking system stability. Unlike unsafe third-party modified ISOs, RL-WinRevive runs safely on standard installations to deliver maximum performance while keeping your native Windows 11 rounded corners and animations fully intact.

### ✨ Key Features
* **Mechanical HDD Optimization:** Disables resource-heavy services like `SysMain` (Superfetch) and `WSearch` to eliminate 100% disk usage spikes.
* **Background Bloat Purge:** Stops telemetry (`DiagTrack`), error reporting (`WerSvc`), and heavy background update orchestrators (`UsoSvc`, `WaaSMedicSvc`).
* **UI Responsiveness:** Restores the classic, instant Windows-style context menu and eliminates menu hover delays.
* **Kernel Overhead Reduction:** Disables Virtualization-Based Security (VBS) CPU drag and optimizes the file system cache (`LargeSystemCache`).
* **Zero Dependencies:** Written entirely in C++ and compiled statically into a tiny standalone binary under 100KB.

---

## 🚀 Quick Start
1. Download the latest `RL-WinRevive.exe` from the **Releases** tab.
2. Right-click the executable and choose **Run as Administrator** (required for service and registry modifications).
3. Type `Y` to apply optimizations, and **restart your PC** for changes to take full effect.

## 📄 License
This project is open-source software licensed under the [MIT License](LICENSE).

---
*Developed with precision by **Riswan-Limaga Enterprises**.*
