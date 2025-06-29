# 🚀 FB SPAM SHARE - Automated Facebook Post Sharing Tool

<div align="center">
  <a href="https://jl-spam-share.onrender.com">
    <img src="https://img.shields.io/badge/%F0%9F%94%A5_LIVE_DEMO-00f0ff?style=for-the-badge&logo=rocket&logoColor=white" alt="Live Demo">
  </a>
  <img src="https://img.shields.io/badge/Version-1.0.0-success?style=for-the-badge" alt="Version">
</div>

![Cyberpunk UI Screenshot](https://i.imgur.com/SfuFOFX.jpeg)

> **🌐 Official Website:** [https://jl-spam-share.onrender.com](https://jl-spam-share.onrender.com)

## ✨ Features

| Feature | Description |
|---------|-------------|
| ⚡ **Instant Sharing** | Automate Facebook post sharing with browser cookies |
| 🎛️ **Precise Control** | Set custom share limits and delays (in milliseconds) |
| 🌓 **Theme Toggle** | Switch between dark/light cyberpunk themes |
| 📈 **Real-time Tracking** | Monitor active processes with progress bars |
| 📚 **History Log** | View past sharing sessions with timestamps |

## 🛠️ Tech Stack

### Frontend
<div>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Font_Awesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white" alt="Font Awesome">
</div>

### Hosting & Deployment
<div>
  <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white" alt="Render">
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare">
</div>

## 🏁 Getting Started

### Prerequisites
- Facebook account
- Valid AppState cookies
- Modern web browser

### Usage Guide
1. **Visit** [jl-spam-share.onrender.com](https://jl-spam-share.onrender.com)
2. **Enter** your Facebook AppState
3. **Paste** target post URL
4. **Configure**:
   - Share limit (e.g., 100)
   - Delay between shares (e.g., 2000ms)
5. **Click** "BOOST NOW"

```mermaid
sequenceDiagram
    User->>Website: Enters AppState + URL
    Website->>Facebook API: Sends share requests
    Facebook API-->>Website: Returns status
    Website->>User: Displays progress
