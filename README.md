# Esp32-camera
# ESP32-CAM WiFi Camera

A feature-complete ESP32-CAM wireless camera system with live MJPEG streaming,
photo capture to mobile, flash control, and physical button capture — all accessible
from a mobile browser with no app required.

---

## Features

- 📡 **WiFi Access Point** — ESP32-CAM creates its own hotspot, no router needed
- 📺 **Live MJPEG Stream** — smooth real-time video in the browser at 20–25 FPS
- 📸 **Photo Capture** — saves images directly to your phone's Downloads folder
- 🔘 **Physical Button** — press GPIO 13 to capture from the hardware
- 💡 **Flash Control** — toggle the onboard LED flash from the browser
- 📊 **Live FPS Counter** — real-time frames-per-second display in browser
- ⚡ **Dual-core architecture** — stream runs on Core 0, controls on Core 1 — no blocking

---

## Hardware Required

| Component | Details |
|---|---|
| ESP32-CAM | AI Thinker board (OV2640 camera) |
| USB-to-Serial adapter | CP2102 or CH340 (for uploading) |
| Push button | Momentary tactile switch |
| Power supply | 5V 2A minimum |
| Jumper wire | For GPIO0 → GND during upload |

---

