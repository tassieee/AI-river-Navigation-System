# 🚢 AI River Navigation System

A real-time maritime navigation dashboard with live weather, flood monitoring, interactive maps, and AI-powered assistance in Bengali.

---

## 🌟 Features

- **Live Weather** — Real-time temperature, wind speed, humidity & 5-day forecast via OpenWeatherMap API
- **Flood Monitoring** — Daily precipitation and flood risk levels via Open-Meteo API
- **Interactive Map** — Leaflet.js + OpenStreetMap with satellite, topographic & street views
- **Route Planning** — Vessel route analysis with AI-generated safety recommendations
- **AI Chat Assistant** — Bengali-language navigation guidance powered by Anthropic Claude API
- **Demo Mode** — Fully functional without API keys

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Map | Leaflet.js + OpenStreetMap |
| Weather API | OpenWeatherMap |
| Flood Data | Open-Meteo (no key required) |
| AI Chat | Anthropic Claude API |
| Fonts | Google Fonts (Tiro Bangla, JetBrains Mono) |

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/river-navigation-system.git
cd river-navigation-system
```

### 2. Open in browser
No build step needed — just open the file directly:
```bash
open river-nav-real.html
```

### 3. Get API Keys (Free)

**OpenWeatherMap**
1. Sign up at [openweathermap.org](https://openweathermap.org/api)
2. Go to API Keys → Copy your key

**Anthropic Claude**
1. Sign up at [console.anthropic.com](https://console.anthropic.com)
2. Go to API Keys → Create new key

### 4. Enter keys on startup
Paste your API keys in the setup modal when the app loads. Or click **"Demo Mode"** to explore without keys.

---

## 📸 Screenshots

> Dashboard with live weather, map, and flood monitoring panels.

---

## 🗺️ Supported Rivers

- পদ্মা নদী (Padma)
- মেঘনা নদী (Meghna)
- যমুনা নদী (Jamuna)
- সুরমা নদী (Surma)
- গঙ্গা নদী (Ganges)
- ব্রহ্মপুত্র নদী (Brahmaputra)
- বুড়িগঙ্গা নদী (Buriganga)
- কর্ণফুলী নদী (Karnaphuli)

---

## 📁 Project Structure

```
river-navigation-system/
│
├── river-nav-real.html     # Main application (single file)
└── README.md               # Project documentation
```

---

## ⚠️ Disclaimer

This project is built for academic and demonstration purposes. Do not rely solely on this system for real maritime navigation decisions. Always follow official maritime authority guidelines.

---

## 👨‍💻 Author

HUMYRA TASMIA

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
