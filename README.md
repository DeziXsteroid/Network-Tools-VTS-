# Network-Tools-VTS (0.8 Beta)

<p align="center">
  <a href="https://github.com/<USER>/<REPO>/releases/latest">
    <img alt="Download" src="https://img.shields.io/badge/Download-Latest%20Release-brightgreen?style=for-the-badge">
  </a>
  <a href="https://github.com/<USER>/<REPO>/releases">
    <img alt="Releases" src="https://img.shields.io/badge/Releases-All-blue?style=for-the-badge">
  </a>
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.10%2B-blue?style=flat-square">
  <img alt="License" src="https://img.shields.io/badge/License-MIT-yellow?style=flat-square">
</p>

**VTS** — десктопный набор сетевых инструментов для инженеров и AV-специалистов: IP Scan, Port Scan, Send Request (TCP/UDP/Serial) и т.д.

---

## ✨ Download
➡️ **Скачать последнюю версию:**  
https://github.com/<USER>/<REPO>/releases/latest

> Рекомендуется скачивать `.zip` из Releases.

---

## 🔥 Features
- **IP Scanner** — скан диапазона, производитель (OUI/manuf), ping
- **Port Scan** — быстрый scan портов
- **Send Request** — TCP / UDP / Serial
- Логи, пресеты, экспорт в Excel (если есть)

---

## 🖼️ Screenshots
<p align="center">
  <img src="assets/screenshots/main.png" width="850">
</p>

---

## 🚀 Quick Start (Windows)
1) Скачай архив из Releases  
2) Распакуй  
3) Запусти `VTScanner.exe`

> При первом запуске может понадобиться интернет для загрузки базы производителей (если так у тебя устроено).

---

## ⚙️ Build from source
```bash
pip install -r requirements.txt
python ui.py
