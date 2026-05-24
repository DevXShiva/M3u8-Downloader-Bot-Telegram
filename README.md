# 🚀 M3U8 Downloader Telegram Bot

Advanced Telegram M3U8 Video Downloader & Uploader Bot powered by **Pyrogram**, **yt-dlp**, and **FFmpeg**.

Automatically downloads `.m3u8` videos, splits large files, generates thumbnails, extracts metadata, and uploads videos directly to Telegram with live progress updates.

---

# ✨ Features

* ✅ Direct `.m3u8` video downloading
* ✅ Fast Telegram uploads
* ✅ Multiple links queue support
* ✅ Auto video splitting for large files (>2GB)
* ✅ Auto thumbnail generation
* ✅ Metadata extraction
* ✅ Streamable Telegram uploads
* ✅ Live upload progress
* ✅ Flask web server support for Render deployment
* ✅ Clean & professional bot structure

---

# 📸 Bot Commands

| Command  | Description                  |
| -------- | ---------------------------- |
| `/start` | Show bot help & features     |
| `/m`     | Download multiple M3U8 links |

---

# 📥 Usage

## ▶️ Single Link Download

Simply send any `.m3u8` link directly to the bot.

Example:

```text
https://example.com/video.m3u8
```

---

## ▶️ Multiple Links Download

Send links using `/m` command.

Example:

```text
/m
https://site.com/1.m3u8
https://site.com/2.m3u8
https://site.com/3.m3u8
```

The bot will process all links sequentially.

---

# 🛠 Requirements

* Python 3.10+
* FFmpeg
* yt-dlp

---

# 📦 Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/DevXShiva/M3u8-Downloader-Bot-Telegram.git
cd M3u8-Downloader-Bot-Telegram
```

---

## 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 3️⃣ Install FFmpeg

### Ubuntu/Debian

```bash
sudo apt update
sudo apt install ffmpeg
```

### Windows

Download FFmpeg from:

https://ffmpeg.org/download.html

---

# ⚙️ Configuration

Create a `config.py` file.

```python
API_ID = "YOUR_API_ID"
API_HASH = "YOUR_API_HASH"
BOT_TOKEN = "YOUR_BOT_TOKEN"
```

---

# ▶️ Run Bot

```bash
python bot.py
```

---

# 🌐 Deploy on Render

## Build Command

```bash
pip install -r requirements.txt
```

## Start Command

```bash
python bot.py
```

---

# 📁 Project Structure

```text
M3u8-Downloader-Bot-Telegram/
│
├── bot.py
├── config.py
├── requirements.txt
├── utils/
│   └── progress.py
└── README.md
```

---

# 📌 Dependencies

```text
pyrogram
tgcrypto
yt-dlp
flask
hachoir
```

---

# 🔥 Powered By

* Pyrogram
* FFmpeg
* yt-dlp
* Flask

---

# ⚠️ Disclaimer

This bot is made for educational and personal use only.

Users are responsible for the content they download or upload.

---

# 💎 Author

Developed with ❤️ for high-speed Telegram media uploading.
