## 2. README.md

```markdown
# 🎵 Thriven Sound Analyzer

> Offline-first CLI tool for DJs & producers to scan, analyze, rank, and export the best audio loops.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/Node.js-18%2B-green.svg)](https://nodejs.org/)

## ✨ Features

- 📂 **Folder Scanner** – Recursively scan audio folders (WAV, MP3, M4A, FLAC)
- 🔊 **Loudness Analysis** – LUFS, Peak, RMS via ffmpeg
- 🔄 **Duplicate Detection** – SHA-256 hash-based
- 📊 **Smart Ranking** – Weighted scoring for loopability
- 📦 **Export Top-N** – Copy best tracks with reports

## 🚀 Quick Start

### Prerequisites

```bash
# macOS
brew install node ffmpeg

# Linux/Debian
sudo apt install nodejs ffmpeg