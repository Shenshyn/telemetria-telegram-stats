<p align="center">
  <img src="assets/logo.png" alt="Telemetria Logo">
</p>

<p align="center">
  <a href="(https://www.linkedin.com/in/shenshyn/)">
    <img alt="My LinkedIn" src="https://img.shields.io/badge/My_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
  <a href="README-ukr.md">
    <img alt="Ukrainian Version" src="https://img.shields.io/badge/%D0%A3%D0%BA%D1%80%D0%B0%D1%97%D0%BD%D1%81%D1%8C%D0%BA%D0%B8%D0%B9_%D0%B2%D0%B0%D1%80%D1%96%D0%B0%D0%BD%D1%82-FFD700?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA5MDAgNjAwIj48cmVjdCB3aWR0aD0iOTAwIiBoZWlnaHQ9IjMwMCIgZmlsbD0iIzAwNTdiZCIvPjxyZWN0IHk9IjMwMCIgd2lkdGg9IjkwMCIgaGVpZ2h0PSIzMDAiIGZpbGw9IiNmZmM3MDAiLz48L3N2Zz4=">
  </a>
</p>

<p align="center">
  <a href="https://github.com/Shenshyn/telemetria-telegram-stats/releases/download/v1.0.0/Telegram.Stats.html">
    <img alt="Download" src="https://img.shields.io/github/release/Shenshyn/telemetria-telegram-stats?style=for-the-badge&color=FFFFFF" /></a>
  <a href="#-getting-started">
    <img alt="Export Guide" src="https://img.shields.io/badge/Export_Guide-505050?style=for-the-badge&logo=telegram&logoColor=white" />
  </a>
</p>

---

# Telemetria - Telegram Chat Statistics

Telemetria is an interactive visualizer for your Telegram chat exports that runs entirely in your browser for **100% privacy**. Just upload your exported folder to transform your personal chat history into an insightful dashboard.

## ✨ Core Features

### 1. The Big Picture & Leadership

Discover your chat duration, total message counts, and even who leads the conversation with detailed percentage breakdowns.

<p align="center">
  <img src="assets/eng_11.png" alt="Screenshot of basic statistics" width="90%">
</p>

### 2. Deep Text Analysis

Dive deep into text analysis with a dynamic word cloud, detailed emoji statistics, average message length, and unique vocabulary tracking.

<p align="center">
  <img src="assets/eng_2.png" alt="Screenshot of text analysis" width="90%">
</p>

### 3. Multimedia Breakdown

See a full breakdown of your media, including total voice message duration, sticker usage, top shared links, photos, and videos.

<p align="center">
  <img src="assets/eng_3.png" alt="Screenshot of media analysis" width="90%">
</p>

### 4. Communication Rhythm

Explore the rhythm of your communication with an interactive timeline, hourly activity heatmaps, and average reply times between users.

<p align="center">
  <img src="assets/eng_4.png" alt="Screenshot of communication dynamics" width="90%">
</p>

### 5. Fun & Achievements

Unlock fun insights with a built-in achievement system, an 'epicenter' feature to find the most-discussed messages, and a nostalgia 'on this day' generator.

<p align="center">
  <img src="assets/eng_5.png" alt="Screenshot of achievements and fun features" width="90%">
</p>

### 6. Chat Comparison

Try out a powerful tool for comparing your statistics (messages, media, voice time) against any other personal chat available in your export file.

<p align="center">
  <img src="assets/eng_6.png" alt="Screenshot of chat comparison feature" width="90%">
</p>

---

## 🚀 Getting Started

<a name="⬇️ Export Instructions"></a>
## ⬇️ Export Instructions

### 1. Export Your Data from Telegram

(If you are on a Mac, you need to download Telegram Lite.)

* Open Telegram and go to: `Settings > Advanced > Export Telegram Data`.
* In the export settings, make sure to check **Personal Chats**. You can uncheck all other types like groups or channels.
* In the “Media export settings” section, select only **Voice Messages**.
* At the bottom, change the format from "HTML" to **"JSON"**.
* Click **Export** and wait for the process to finish. The process is usually quite slow, so you need to be patient. Telegram will save the folder with your data in the `Telegram Desktop` folder.

<p align="center">
    <img alt="Telegram Export Settings Screenshot" src="https://github.com/user-attachments/assets/dd231b58-b044-46cf-a25b-70494e4bc159" width="70%">
</p>

### 2. Get Your Stats

* Download the single `index.html` file from this repository's **[Releases](https://github.com/Shenshyn/telemetria-telegram-stats/releases)** page.
* Open the downloaded `index.html` file in your browser.
* Click the "Select history folder" button.
* Select the **entire folder** (not a single file) that Telegram just exported.
* Your browser will show a pop-up asking for permission to read the files. Click "Upload" or "Allow".
* That's it! Select the chat you want to analyze from the list and enjoy your stats.

***

### 🔒 Privacy Notice

This tool is **100% private**. All data processing is performed **locally in your browser**. Your chat files are **never uploaded to any server**.
