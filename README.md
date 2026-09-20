# FlowShield — Website & Android App

FlowShield is a Bengaluru-focused flood-intelligence **simulation/prototype** available as a desktop website and Android app.
Created with the help of Gemini and ChatGPT.

## Project Files

```text
FlowShield/
├── README.md
├── flowshield.html
└── FlowShield-search-final.apk
```

## 1. Website — `flowshield.html`

Open `flowshield.html` in a modern browser.

### Main Features

- **Bengaluru Monsoon Intelligence dashboard** for simulated flood conditions
- **Storm scenarios:** Normal Monsoon (60 mm/hr), Cloudburst / Flash Flood (150 mm/hr), Rajakaluve Blockage & Encroachment (110 mm/hr), and Custom
- **Simulation controls:** rainfall intensity 10–250 mm/hr, storm duration 1–12 hours, play/pause, reset and timeline
- **Topographic Matrix & Hydrology:** elevation, population, location, simulated water depth and risk categories
- **Intervention simulation:** pumps, flood barriers and drainage/siltation effects
- **SEARCH YOUR AREA:** search Bengaluru simulation zones such as Indiranagar, Bellandur, Silk Board and Whitefield
- **GIS flood map** with Bengaluru geographic visualization
- **3D terrain & surface-water visualization**
- **Flood analytics and automated action protocols**
- **AI Copilot interface** for simulation-based queries and action planning
- **CSV advisory export**
- **Rain ambience and storm visual effects**

> The website uses simulated data. It is not an official real-time flood-warning system.

## 2. Android App — `FlowShield-search-final.apk`

The Android version packages the FlowShield experience for phones and adds a mobile-oriented interface.

### Android Additions

- Fixed mobile bottom navigation: **Home / Map / Trends / Help**
- Compact, touch-friendly mobile layout
- Mobile-friendly visualization and dashboard presentation
- **SEARCH YOUR AREA** for finding simulation zones quickly

## 3. Website vs Android

| Feature | Website | Android |
|---|:---:|:---:|
| Flood simulation & storm scenarios | ✓ | ✓ |
| Hydrology / risk dashboard | ✓ | ✓ |
| GIS map | ✓ | ✓ |
| 3D terrain | ✓ | ✓ |
| Interventions | ✓ | ✓ |
| AI Copilot interface | ✓ | ✓ |
| Search Your Area | ✓ | ✓ |
| Mobile bottom navigation | — | ✓ |
| Mobile-specific layout | — | ✓ |

## 4. Open-Source Libraries & External Components

The current `flowshield.html` uses:

| Library / Component | Version / Source | Use |
|---|---|---|
| **Tailwind CSS** | CDN | Styling and responsive UI |
| **Chart.js** | CDN | Charts / analytics |
| **Three.js** | r128 | 3D terrain and water visualization |
| **Leaflet** | 1.9.4 | Interactive flood map |
| **Font Awesome** | 6.5.1 | Icons |
| **Plus Jakarta Sans** | Google Fonts | Typography |
| **CARTO + OpenStreetMap** | Map tiles / attribution | Map base layer |

These web dependencies are loaded from external CDNs/services, so internet access is normally required for all website features to load correctly.

## 5. AI Note

The AI Copilot interface is included, but the supplied HTML does **not** contain a configured Gemini API key. Live AI responses therefore require separate configuration/backend setup.

For production, API keys should be kept on a secure backend rather than exposed in client-side HTML.

## 6. Prototype Notice

FlowShield simulates rainfall, inundation, terrain response, risk levels and intervention effects. Results should not be treated as official hydrological measurements, emergency instructions or real-time government alerts.

## 7. Running the Project

### Website

1. Open `flowshield.html` in a modern browser.
2. Choose a storm scenario.
3. Adjust rainfall and duration.
4. Run the simulation and explore the map, trends, 3D view and interventions.

### Android

Install `FlowShield-search-final.apk` on a compatible Android device and use the mobile navigation to explore the same simulation experience.
