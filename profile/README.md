<div align="center">

  <img src="assets/logo.png" alt="Zenso Mark" width="96" height="96" />

  # Zenso
  
  **A window to calm living.**

  Smart, connected e-Paper displays and an open widget platform designed for ambient, distraction-free spaces.

  <p align="center">
    <a href="https://zenso.ink"><strong>zenso.ink</strong></a> •
    <a href="https://discord.gg/vTjzkwz3XV"><strong>Join Discord</strong></a> •
    <a href="mailto:zensoink@gmail.com"><strong>zensoink@gmail.com</strong></a>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/e--Paper-Monochrome%20·%20Grayscale%20·%20Multi--Color-24292e?style=flat-square" alt="e-Paper Support" />
    <img src="https://img.shields.io/badge/Hardware-ESP32--S3-000000?style=flat-square&logo=espressif" alt="ESP32-S3" />
    <img src="https://img.shields.io/badge/Widgets-Liquid%20%2B%20HTML%2FCSS-008080?style=flat-square" alt="LiquidJS" />
    <img src="https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=flat-square&logo=discord&logoColor=white" alt="Discord" />
  </p>

</div>

---

### 🌿 What is Zenso?

Zenso reimagines smart home dashboards and digital photo frames as **calm technology**. Instead of glowing screens, notification banners, and aggressive backlights, Zenso uses physical **e-Paper displays** that look and feel like museum-grade printed paper.

- 🎨 **Universal Display Support**: Works with any e-paper display — from monochrome and grayscale panels to vivid 7-color ACeP/Spectra screens. Custom resolutions and color palettes can be configured directly in settings.
- ☀️ **Natural Paper Texture**: High-contrast, matte, and completely glare-free in direct sunlight or ambient room light.
- 🔋 **Weeks of Battery Life**: Deep-sleep hardware design waking up only to refresh content silently over Wi-Fi.
- ⚡ **Zero-JS on Device**: Content is rendered server-side (Liquid → HTML/CSS → Headless Chromium → Dithered bitmap) and fetched as an optimized static image.

---

### 🔌 Official Widgets & Plugins

Zenso widgets turn any e-paper display into a thoughtful, glanceable dashboard or photo frame:

| Plugin | Description | Source |
|:---|:---|:---:|
| 📅 **Calendar** | **Live agenda for Google Calendar & Apple iCloud.**<br/>Subscribes to your existing schedules via standard ICS feeds. Features clean month, week, and list layouts with high-contrast typography designed specifically for e-paper. | [**plugin-calendar**](https://github.com/zensoink/plugin-calendar) |
| 🖼️ **Photo & Art** | **Ambient photo frame and dynamic imagery.**<br/>Display cherished photos, webcam captures, weather radars, or daily art. Supports responsive scaling (`cover` / `contain`), LAN and cloud endpoints, and contrast optimization. | [**plugin-image**](https://github.com/zensoink/plugin-image) |
| 🧩 **Starter Template** | **Build your own custom e-ink widget in minutes.**<br/>A ready-to-use template equipped with a local Vite dev server, Hot Module Replacement (HMR), mock data layers, and one-command packaging. | [**zenso-plugin-template**](https://github.com/zensoink/zenso-plugin-template) |

---

### 🛠️ Developer SDK & Firmware

The Zenso platform provides open developer tooling and firmware for building custom widgets and hardware:

- **[zenso-firmware](https://github.com/zensoink/zenso-firmware)** — Open source ESP32-S3 firmware. Includes captive portal Wi-Fi provisioning, display controller integration, deep sleep power management, and OTA updates. *(GPL-3.0)*
- **[vite-plugin](https://github.com/zensoink/vite-plugin)** (`@zenso/vite-plugin`) — Build tooling for Liquid template compilation, schema validation, and `plugin.zip` packaging. *(Apache-2.0)*
- **[zenso-schemas](https://github.com/zensoink/zenso-schemas)** — JSON schemas defining plugin manifests and configuration contracts. *(Apache-2.0)*

---

### 🚀 Creating Your First Plugin

You can develop, test, and preview new widgets locally using standard web technologies:

```bash
# 1. Clone the starter template
git clone https://github.com/zensoink/zenso-plugin-template my-zenso-widget
cd my-zenso-widget

# 2. Install dependencies
npm install

# 3. Start local development with hot reload and mock datasets
npm run dev

# 4. Package your plugin into plugin.zip
npm run build
```

Check out the **[Plugin Authoring Guide](https://github.com/zensoink/zenso-plugin-template/blob/master/GUIDE.md)** for details on configuration schemas, server-side data feeds, and design tips for e-paper.

---

### 💬 Community & Connect

Join our growing community of hardware makers, designers, and e-paper enthusiasts:

- 💬 **Discord**: [discord.gg/vTjzkwz3XV](https://discord.gg/vTjzkwz3XV)
- ✉️ **Email**: [zensoink@gmail.com](mailto:zensoink@gmail.com)
- 🌐 **Website**: [zenso.ink](https://zenso.ink)

<div align="center">
  <sub>Crafted with tranquility by <a href="https://zenso.ink">Zenso</a>.</sub>
</div>
