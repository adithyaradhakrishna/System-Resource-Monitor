# 🖥️ System Resource Monitor — Real-Time Python Desktop Utility

A simple yet powerful Python-based tool that provides **real-time system resource monitoring**. It displays **CPU, RAM, disk, and network usage** using live plots generated with `matplotlib` and data collected via `psutil`. Great for debugging, performance monitoring, or learning system internals.

---

## 📝 Description

This tool gives users a visual overview of current system activity, helping identify performance bottlenecks and better understand how system resources are being utilized.

---

## ✨ Features

- 📈 **Real-time monitoring** of:
  - CPU usage (core-wise and total)
  - RAM (used, available)
  - Disk I/O
  - Network bandwidth
- 🖼️ **Live updating plots** using `matplotlib`
- 🔄 Auto-refreshing data feed for live insights
- ⚡ Lightweight and responsive — ideal for quick diagnostics

---

## 💻 Technologies Used

- **Python 3.x**
- `psutil` — for system performance metrics
- `matplotlib` — for plotting real-time graphs
- `time`, `threading`, `tkinter` (optional) — for responsiveness and layout

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/system-resource-monitor.git
cd system-resource-monitor
