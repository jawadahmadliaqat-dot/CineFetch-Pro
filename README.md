<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Righteous&color=00E5FF&size=52&center=true&vCenter=true&width=900&lines=CineFetch+Pro;Fast+%26+Lightweight+Video+Downloader;Android+Automation+with+Style" alt="CineFetch Pro" />
</div>

<p align="center">
  <strong>Fast, lightweight, privacy-focused video downloading for Android and automation workflows.</strong>
</p>

<p align="center">
  <a href="https://github.com/jawadahmadliaqat-dot/CineFetch-Pro/releases">
    <img src="https://img.shields.io/github/downloads/jawadahmadliaqat-dot/CineFetch-Pro/total?style=for-the-badge&logo=github&color=2ecc71" alt="Downloads" />
  </a>
  <a href="https://github.com/jawadahmadliaqat-dot/CineFetch-Pro/releases">
    <img src="https://img.shields.io/github/v/release/jawadahmadliaqat-dot/CineFetch-Pro?style=for-the-badge&logo=android&color=3498db" alt="Latest Release" />
  </a>
  <img src="https://img.shields.io/github/license/jawadahmadliaqat-dot/CineFetch-Pro?style=for-the-badge&color=e74c3c" alt="License" />
  <img src="https://img.shields.io/github/stars/jawadahmadliaqat-dot/CineFetch-Pro?style=for-the-badge&color=f1c40f" alt="Stars" />
</p>

<table>
  <tr>
    <td width="65%">
      <h3>🎬 About</h3>
      <p>
        <strong>CineFetch Pro</strong> is a modern, privacy-focused Android and automation-friendly downloader built for speed, reliability, and a clean experience.
        It combines fast downloads, smart processing, usage tracking, and a lightweight workflow that feels premium without the bloat.
      </p>
      <p>
        Built for real-world use, it keeps the UI responsive while running downloads, FFmpeg processing, and cleanup jobs in the background.
      </p>
    </td>
    <td width="35%">
      <h3>📊 Quick Snapshot</h3>
      <p>• Downloads: queue-based and fast</p>
      <p>• UI: smooth Flet-based experience</p>
      <p>• Pipeline: Download → Process → Save → Cleanup</p>
      <p>• Reliability: crash-resistant logging</p>
    </td>
  </tr>
</table>

## ✨ Core Features

| Feature | Details |
| --- | --- |
| ⚡ Ultra-Fast Downloads | Optimized background processing keeps the app responsive while downloads and processing continue in parallel. |
| 🛡️ Privacy First | Minimal permissions, lightweight design, and user-focused handling of media files. |
| 🎯 Smart Automation | Batch URL handling, session-based unlocking, daily limits, and usage tracking. |
| 🧩 Clean UI | Modern, simple interface with status updates, progress flow, and notifications. |
| 🧪 Reliability | Error isolation, safe cleanup, and local logging to prevent crashes during heavy use. |
| 🎨 Premium Feel | Polished, modern experience designed for smooth workflows and easy day-to-day use. |

## 🧭 Supported Platforms

CineFetch Pro is designed for downloading content from popular services such as:

- YouTube
- Facebook
- Instagram
- Twitter / X
- TikTok
- And more...

## 🖥️ System Requirements

- Android 8.0+ (Oreo and newer)
- Minimum 50 MB free storage
- Internet connection for downloading
- FFmpeg available for media processing

## 🏗️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,android,flet,git,github,vscode,ffmpeg" alt="Tech Stack" />
</p>

## 🚀 Workflow

```text
Watch Ad / Unlock Session
        ↓
Enter Video URLs
        ↓
Run Batch Download
        ↓
Process with FFmpeg
        ↓
Save Final Output
        ↓
Cleanup Raw Files
```

## 📦 Project Structure

```text
CineFetch-Pro/
├── main.py              # Main Flet app and UI state
├── scraper.py           # Batch scraping logic
├── processor.py         # FFmpeg processing pipeline
├── utils.py             # Logging, usage tracking, helpers
├── config.py            # Configuration and paths
├── data/
│   ├── processed/       # Final processed media
│   └── raw/             # Temporary raw downloads
├── logs/
│   ├── app.log          # App activity log
│   └── error_log.txt    # Error tracebacks
├── usage.json           # Daily usage tracking
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation
├── build_release_fresh.ps1
├── setup.py
├── scraper.py
└── main.spec
```

## ⚙️ Core Features in Detail

### 1) Ad-Gateway Session Logic
```text
Watch Ad → 10 second countdown → Unlock 3 downloads
Session resets after processing the allowed batch
```

### 2) Usage Tracker
- Tracks daily usage and total downloads
- Prevents overuse beyond daily limits
- Persists to JSON and auto-resets on date change

### 3) FFmpeg Processing Pipeline
```text
Input Video → Scale & Crop → Speed Adjustment → Brightness/Saturation → Strip Metadata → Save Output
```

### 4) Background Concurrency Model
- Main thread handles UI rendering
- Worker threads manage scraping and processing
- Queue-based updates keep the interface responsive

### 5) Error Handling
- External calls are wrapped in exception handling
- Failures are logged locally for debugging
- User-facing notifications show what failed

## 🛠️ Installation

### Install dependencies
```bash
pip install -r requirements.txt
```

### Run locally
```bash
python main.py
```

## 📥 Download

Get the latest version from the official GitHub release page:

<p align="center">
  <a href="https://github.com/jawadahmadliaqat-dot/CineFetch-Pro/releases/download/v2.1.0/CineFetch-Pro.apk">
    <img src="https://img.shields.io/badge/Download%20APK-v2.1.0-success?style=for-the-badge&logo=android&logoColor=white&color=27ae60" alt="Download APK" />
  </a>
</p>

## 🧪 Changelog

### v2.1.0
- Improved download speed
- Interface polish
- Stability and performance fixes

### v2.0.0
- Major performance update
- Better stability and workflow improvements

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Open a pull request

## 🛟 Support

If you run into issues, open an issue in this repository and describe the bug, environment, and steps to reproduce.

## ⚖️ Disclaimer

This project is intended for downloading content that you have legal permission to access. Please respect copyright laws and the terms of service of the platforms you use.

## 📜 License

This project is open source and available under the repository license.

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=jawadahmadliaqat-dot&style=flat-square&color=00E5FF" alt="Profile Views" />
</p>

<p align="center">
  <b>Made with ❤️ by Jawad Ahmad</b>
</p>

---

## ✅ Important Note

The previous version used unsupported custom CSS in a GitHub README, which rendered as raw code instead of styled content. This version is rebuilt for GitHub compatibility, so it will display correctly and still look modern, premium, and clean.


