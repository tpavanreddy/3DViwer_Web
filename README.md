# TerraStudio3D

**UAV Survey & 3D Mapping Platform by [TerraOrbit](https://www.terraorbit.in)**

![TerraStudio3D](https://img.shields.io/badge/TerraStudio3D-v1.0-blue)
![License](https://img.shields.io/badge/License-Proprietary-orange)
![Platform](https://img.shields.io/badge/Platform-Web-green)

---

## 🌍 Overview

**TerraStudio3D** is a professional web-based UAV survey and mapping data visualization platform. Display orthomosaics, GeoJSON layers, and perform measurements on aerial imagery captured by drones.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🗺️ **Multi-Basemap Support** | Google Streets, OSM, CartoDB, Esri Imagery, OpenTopo |
| 🛰️ **UAV Orthomosaic Display** | TMS tile layer support for drone imagery |
| 🏢 **GeoJSON Layers** | Building footprints with attributes (Area, Perimeter) |
| 📏 **Measurement Tools** | Distance and area measurement |
| ✏️ **Drawing Tools** | Annotate and draw shapes on map |
| 🗺️ **Minimap** | Overview navigation control |
| 📍 **Mouse Position** | Real-time coordinate display |
| 🎛️ **Layer Control** | Toggle basemaps and overlays |

---

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Edge, Safari)
- Web server (optional, for local development)

### Quick Start

1. Clone the repository
```bash
git clone <repository-url>
cd terrastudio3d
```

2. Open in browser
```bash
# Simply open index.html in your browser
# Or use a local server:
python -m http.server 8000
```

3. Visit `http://localhost:8000`

---

## 📁 Project Structure

```
terrastudio3d/
├── index.html              # Main application (TerraStudio3D)
├── hellomap.html           # Legacy map file
├── styles.css              # Main stylesheet
├── geojson_data/           # GeoJSON data files
│   └── Buildings.geojson   # Building footprints
├── orthotile/              # UAV orthomosaic tiles (TMS)
│   └── {z}/{x}/{y}.png
├── plugins/                # Leaflet plugins
│   ├── ajax/               # AJAX GeoJSON loader
│   ├── minimap/            # Minimap control
│   ├── mouseposition/      # Mouse position control
│   └── sidebar/            # Sidebar control
└── source/                 # jQuery UI assets
```

---

## 🛠️ Technologies Used

- **[Leaflet.js](https://leafletjs.com/)** - Interactive maps
- **[Bootstrap](https://getbootstrap.com/)** - UI framework
- **[jQuery](https://jquery.com/)** - JavaScript library
- **[Leaflet Geoman](https://geoman.io/)** - Drawing tools
- **[Font Awesome](https://fontawesome.com/)** - Icons

---

## 🎨 Branding

| Element | Value |
|---------|-------|
| **Product Name** | TerraStudio3D |
| **Company** | TerraOrbit |
| **Website** | [www.terraorbit.in](https://www.terraorbit.in) |
| **Primary Color** | `#1a237e` (Deep Blue) |
| **Accent Color** | `#4fc3f7` (Light Blue) |

---

## 📄 License

Proprietary - © 2024 TerraOrbit. All rights reserved.

---

## 📞 Contact

**TerraOrbit**
- 🌐 Website: [www.terraorbit.in](https://www.terraorbit.in)
- 📧 Email: info@terraorbit.in
- 📍 Location: India

---

<p align="center">
  <strong>TerraStudio3D</strong> - Professional UAV Mapping Platform<br>
  Powered by <a href="https://www.terraorbit.in">TerraOrbit</a>
</p>
