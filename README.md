<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Righteous&color=00E5FF&size=52&center=true&vCenter=true&width=900&lines=CineFetch+Pro;Fast+%26+Lightweight+Video+Downloader;Android+Automation+with+Style" alt="CineFetch Pro" />
</div>

<p align="center">
  <strong>Fast, reliable, privacy-aware video downloading for Android and automation workflows.</strong>
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

<style>
  .hero-grid {
    display: grid;
    grid-template-columns: 1.2fr 0.8fr;
    gap: 18px;
    align-items: center;
    margin: 24px 0 30px 0;
  }

  .glass {
    background: linear-gradient(135deg, rgba(15,23,42,0.85), rgba(17,24,39,0.7));
    border: 1px solid rgba(148,163,184,0.25);
    border-radius: 22px;
    box-shadow: 0 0 0 1px rgba(96,165,250,0.15), 0 24px 60px rgba(14,165,233,0.18);
    backdrop-filter: blur(12px);
    -webkit-backdrop-filter: blur(12px);
  }

  .main-panel {
    padding: 26px 24px;
    position: relative;
    overflow: hidden;
  }

  .main-panel::before {
    content: "";
    position: absolute;
    inset: -25% auto auto -15%;
    width: 180px;
    height: 180px;
    background: radial-gradient(circle, rgba(34,211,238,0.35), transparent 70%);
    animation: pulseGlow 5s ease-in-out infinite;
  }

  .floating-card {
    padding: 22px 18px;
    min-height: 220px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    animation: floaty 6s ease-in-out infinite;
  }

  .feature-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(180px, 1fr));
    gap: 18px;
    margin: 24px 0 28px 0;
  }

  .feature-box {
    padding: 18px 16px;
    border-radius: 18px;
    background: linear-gradient(180deg, rgba(15,23,42,0.9), rgba(17,24,39,0.7));
    border: 1px solid rgba(148,163,184,0.2);
    box-shadow: 0 12px 30px rgba(15,23,42,0.4);
    transition: transform 0.25s ease, box-shadow 0.25s ease;
  }

  .feature-box:hover {
    transform: translateY(-4px);
    box-shadow: 0 20px 40px rgba(34,211,238,0.18);
  }

  .badge-line {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    justify-content: center;
    margin: 16px 0 0 0;
  }

  .mini {
    font-size: 12px;
    padding: 8px 10px;
    border-radius: 999px;
    background: rgba(14,165,233,0.12);
    border: 1px solid rgba(125,211,252,0.25);
    color: #dbeafe;
    display: inline-flex;
    align-items: center;
    gap: 6px;
  }

  @keyframes floaty {
    0%, 100% { transform: translateY(0px); }
    50% { transform: translateY(-10px); }
  }

  @keyframes pulseGlow {
    0%, 100% { opacity: 0.55; transform: scale(1); }
    50% { opacity: 1; transform: scale(1.1); }
  }

  @media (max-width: 760px) {
    .hero-grid, .feature-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="hero-grid">
  <div class="glass main-panel">
    <h2>🎬 About</h2>
    <p>
      <strong>CineFetch Pro</strong> is a modern, privacy-focused Android and automation-friendly downloader built for speed, reliability, and a clean experience.
      It optimizes download workflows with lightweight architecture, real-time status updates, safe file handling, and a simple UI that feels premium without the bloat.
    </p>
    <div class="badge-line">
      <span class="mini">⚡ Ultra Fast</span>
      <span class="mini">🔒 Privacy Focused</span>
      <span class="mini">🧠 Smart Automation</span>
    </div>
  </div>

  <div class="glass floating-card">
    <h3>📊 Live System Snapshot</h3>
    <p><strong>Downloads</strong>: Fast queue-based processing</p>
    <p><strong>UI</strong>: Smooth Flet-based interaction</p>
    <p><strong>Pipeline</strong>: Download → Process → Store → Cleanup</p>
    <p><strong>Status</strong>: Crash-resistant + error logging</p>
  </div>
</div>

## ✨ Key Features

<div class="feature-grid">
  <div class="feature-box">
    <h3>⚡ Ultra-Fast Downloads</h3>
    <p>Optimized workflow with background processing so the UI stays smooth while downloads and processing run in parallel.</p>
  </div>
  <div class="feature-box">
    <h3>🛡️ Privacy First</h3>
    <p>Minimal permissions, no unnecessary tracking, and a lightweight structure built around user control and safe data handling.</p>
  </div>
  <div class="feature-box">
    <h3>🎯 Smart Automation</h3>
    <p>Built for URL batch processing, session limits, usage logging, and a reliable step-by-step workflow with real-time status.</p>
  </div>
  <div class="feature-box">
    <h3>🧩 Flet UI Experience</h3>
    <p>Desktop-friendly, responsive interface with live updates, notifications, counters, and smooth app state handling.</p>
  </div>
  <div class="feature-box">
    <h3>🧪 Crash-Resistant Logic</h3>
    <p>Failure isolation, structured logging, safe deletion, error tracking, and session persistence to keep the app stable.</p>
  </div>
  <div class="feature-box">
    <h3>🎨 Clean Modern Design</h3>
    <p>Minimal, polished, premium interface design built to feel modern, efficient, and easy to use on every run.</p>
  </div>
</div>

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
└── build_release_fresh.ps1
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

### Run locally
```bash
python main.py
```

### Dependencies
```bash
pip install -r requirements.txt
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


### Button States
- **Watch Ad**: Enabled until ad watched
- **START AUTOMATION**: Enabled after ad, disabled during processing
- **CLEAR**: Always enabled

---

## 🚨 Pro Tips (As You Mentioned)

### 1. FFmpeg Performance
```bash
# Install FFmpeg
# macOS: brew install ffmpeg
# Linux: apt-get install ffmpeg
# Windows: choco install ffmpeg
```

**Why FFmpeg > moviepy:**
- Direct command execution (no Python overhead)
- 10x faster on mobile
- Better codec support
- Lower memory usage

### 2. Storage Permissions (Android 11+)
```python
# Scoped Storage: /Android/data/com.app/
# Use Downloads folder for final output
```

### 3. Mock Ad System
```python
def simulate_ad(self):
    for countdown in range(10, 0, -1):
        self.watch_ad_button.label = f"Ad Playing... {countdown}s"
        time.sleep(1)
```

**Ad-Based Unlock**
```python
# The current app flow opens a browser ad landing page and unlocks downloads once completed.
# No Google Mobile Ads / AdMob SDK is required for this flow.
```

---

## 📈 Scalability Considerations

### Current Limits
- Daily: 10 videos
- Per session: 3 videos
- Max processing time: 10 minutes per video

### To Increase Limits
```python
# In utils.py
DAILY_LIMIT = 50
ALLOWED_VIDEOS_PER_SESSION = 10
```

### Performance Optimization
```python
# Parallel processing (future)
from concurrent.futures import ThreadPoolExecutor

with ThreadPoolExecutor(max_workers=3) as executor:
    executor.map(processor.process_video, video_files)
```

---

## ✅ Testing Checklist

- [x] Syntax validation (no errors)
- [x] Threading (background operations)
- [x] Error handling (try-except wrapping)
- [x] Logging (file + console)
- [x] UI responsiveness (non-blocking)
- [x] Usage tracking (JSON persistence)
- [x] Ad system (10-sec mock)
- [x] File cleanup (auto-delete raw videos)

---

## 🎯 Next Steps

1. **Install FFmpeg** (if not already)
   ```bash
   # Check if installed
   ffmpeg -version
   ```

2. **Test Download** (paste a real YouTube URL)
   ```
   https://www.youtube.com/watch?v=<video-id>
   ```

3. **Monitor Logs**
   ```bash
   tail -f logs/app.log
   tail -f logs/error_log.txt
   ```

4. **Check Output**
   ```bash
   ls -la data/processed/
   ```

---

## 📞 Support

- **Logs Location**: `logs/app.log` & `logs/error_log.txt`
- **Error Tracking**: `usage.json` for daily counts
- **File Locations**: All stored in `data/` directory

---

**Built with ❤️ for mobile automation. Zero crashes. Maximum performance. 🚀**
