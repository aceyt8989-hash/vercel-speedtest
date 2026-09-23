# ▲ Vercel Speed Test

A clean, minimalist, high-precision internet speed test web application designed with the **Vercel Geist Design System**.

![Vercel Theme](https://img.shields.io/badge/theme-Vercel%20Geist-black?style=flat-square&logo=vercel)
![Zero Dependencies](https://img.shields.io/badge/dependencies-zero-success?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

---

## Features

- **Geist Design System**:
  - High-contrast monochromatic aesthetic (pitch-black `#000` with subtle dot-matrix grid and crisp Geist typography).
  - One-click Dark / Light theme toggle.
  - Tabular numerals (`font-variant-numeric: tabular-nums`) to prevent layout jitter during real-time speed counting.
  - Pulsing status badges (`● READY`, `● TESTING DOWNLOAD`, `● TESTING UPLOAD`).
  - Sleek SVG circular speedometer gauge.
- **Accurate Multi-Stream Engine**:
  - **Ping & Jitter**: Consecutive high-precision latency probing to edge nodes.
  - **Download Speed**: Adaptive parallel multi-chunk streaming (from 1MB to 25MB+) to saturate fast broadband and fiber connections.
  - **Upload Speed**: Multi-stream chunked payloads with real-time throughput tracking.
  - **Bufferbloat Rating**: Grades connection stability under load (`A+`, `A`, `B`, `C`, `D`).
- **Real-Time Visualizations**:
  - High-DPI Canvas throughput graph plotting live bandwidth curves over time.
- **Network Telemetry**:
  - Automatic detection of Public IP, ISP / ASN, Edge Colocation Airport Code (e.g. `SJC`, `FRA`, `BOM`), and Protocol (`HTTP/2`).
- **Utility & Productivity**:
  - Unit switching (`Mbps`, `MB/s`, `Gbps`).
  - Keyboard shortcut: Press `Space` to start or stop testing.
  - Test History saved locally in `localStorage`.
  - One-click Markdown Summary copy for sharing in Discord, Slack, or GitHub.
  - Export test history to JSON.
  - Dual Mode: Cloudflare Global Edge or Local Node.js loopback benchmark.
