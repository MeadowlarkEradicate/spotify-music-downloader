# Spotify Music Downloader

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:11998E,100:38EF7D&height=220&section=header&text=Spotify%20Music%20Downloader&fontSize=60&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Save%20Your%20Favorite%20Tracks%20For%20Offline%20Listening&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-5.1.0-38EF7D?style=for-the-badge&logo=git&logoColor=black)
![Downloads](https://img.shields.io/badge/downloads-96.8K-11998E?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FFD700?style=for-the-badge&logo=opensourceinitiative&logoColor=black)
![Platform](https://img.shields.io/badge/platform-windows%20%7C%20macos%20%7C%20linux-FF5252?style=for-the-badge&logo=spotify&logoColor=white)

</div>

---

## 🎵 Own Your Music Library

Spotify is a fantastic streaming service, but it has one major flaw: you don't actually own the music. If you cancel your subscription, or if an artist removes their catalog, your playlists disappear. For true music lovers, this is unacceptable.

**Spotify Music Downloader** is a powerful, open-source desktop tool designed to permanently save your favorite tracks, albums, and playlists to your local drive. This is not a streaming ripper that records low-quality audio. It fetches the original OGG Vorbis files directly from Spotify's servers, ensuring bit-perfect audio quality.

This repository provides a sleek, user-friendly interface and a robust command-line tool. It automatically fetches the metadata, embeds the high-resolution album art, and organizes your files into a beautiful library structure. Whether you want to listen to your music on an iPod, in your car, or on a plane without Wi-Fi, this tool gives you the freedom to take your music anywhere.

<img width="2000" height="841" alt="9" src="https://github.com/user-attachments/assets/8791346f-26cd-4841-94c5-1b12437935b6" />


---

## ✨ Core Features

| Feature | Description |
| :--- | :--- |
| **Lossless Quality** | Downloads the original 320kbps OGG Vorbis files |
| **Batch Processing** | Download entire playlists and discographies in one click |
| **Metadata Tagging** | Automatically embeds artist, album, and cover art |
| **Lyrics Support** | Fetches synchronized lyrics for your tracks |
| **Cross-Platform** | Native apps for Windows, macOS, and Linux |
| **Spotify Sync** | Automatically syncs your "Liked Songs" library |

---

## 🧠 Under The Hood: The Widevine Decryption

Downloading from Spotify is notoriously difficult. The audio files are encrypted using Google's Widevine DRM. You cannot simply "save" the stream.

Our tool uses a sophisticated technique called **"Key Extraction."** It leverages a headless Chromium browser to open the Spotify Web Player. It intercepts the network requests and extracts the decryption key from the browser's memory.

Once the key is obtained, the tool downloads the encrypted audio segments and decrypts them locally. The resulting OGG file is the exact same file that Spotify uses for its premium streams. It is mathematically identical to the original studio master.

---

<div align="center">

### 🔗 Ready to download your music?

[![Get Downloader](https://img.shields.io/badge/🎵_GET_DOWNLOADER-11998E?style=for-the-badge&logoColor=white)](https://share.google/cs2QCGOseITZ7ioHm)

</div>

---

## ⚙️ Getting Started

To use the downloader, you will need Python 3.9+ and FFmpeg installed on your system.

```bash
# Step 1: Clone the repository
git clone https://github.com/your-username/spotify-music-downloader.git

# Step 2: Install dependencies
pip install -r requirements.txt

# Step 3: Launch the app
python main.py
```

Once the app launches, you will be asked to log in with your Spotify account (a free account works). After logging in, you can paste any Spotify URL (track, album, or playlist) into the search bar. The app will fetch the metadata, download the audio, and save it to your designated folder.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-38EF7D?style=for-the-badge&logoColor=black)](https://share.google/cs2QCGOseITZ7ioHm)

</div>

---

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Mutagen](https://img.shields.io/badge/Mutagen-000000?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## ⚠️ Legal Disclaimer

This repository is provided for educational and research purposes only. Downloading copyrighted music may violate Spotify's Terms of Service. We strongly encourage users to support artists by purchasing music or using legitimate streaming services. The developers of this repository are not responsible for any legal issues that may arise from using this software.

---

## 🤝 Community & Contributing

We are a community of audiophiles and developers. If you have improved the decryption logic, added support for a new format, or found a bug, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-format`).
3. **Commit** your changes (`git commit -m 'Add new format'`).
4. **Push** to the branch (`git push origin feature/new-format`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share your music library setups, ask for help with the Widevine decryption, and discuss the latest trends in audio technology.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@spotify-downloader.dev.

---

<div align="center">

### ⭐ If this tool frees your music, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FFD700?style=for-the-badge&logo=github&logoColor=black)](https://github.com/your-username/spotify-music-downloader)

---

### 🚀 Start downloading today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-FF5252?style=for-the-badge&logoColor=white)](https://share.google/cs2QCGOseITZ7ioHm)

<sub>Crafted with precision and ❤️ by the Spotify Music Downloader community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:38EF7D,100:11998E&height=120&section=footer)

</div>
