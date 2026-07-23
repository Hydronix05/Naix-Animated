# ⚡ NAIX ANIMATED

**Animation for everyone - lightweight, powerful, yours.**

---

## 📌 About

Naix Animated is a free, browser-based animation tool designed for people who can't run heavy animation software on their devices. Whether you're on a Chromebook, an old laptop, or a tablet, Naix Animated gives you the power to create frame-by-frame animations without any installation or hardware requirements.

**Perfect for:**
- Students learning animation
- Artists with low-end devices
- Quick prototyping and storyboarding
- Anyone who wants to animate without the bloat

---

## ✨ Features (v1.0)

| Feature | Description |
|---------|-------------|
| 🖊️ **Freehand Drawing** | Brush with color picker and adjustable size (1-30px) |
| 📽️ **Frame Management** | Add, delete, and navigate between frames |
| ▶️ **Playback** | 12fps smooth animation preview |
| 💾 **Export Video** | Save as WEBM format (plays everywhere) |
| 💿 **Save/Load** | Project files with `.naix` extension |
| 🖼️ **Timeline** | Visual thumbnails of all frames |
| ⌨️ **Keyboard Shortcuts** | Full keyboard control for faster workflow |
| 📱 **Touch Support** | Works on tablets and touchscreens |
| 🌙 **Dark Theme** | Easy on the eyes for long sessions |

---

## 🚀 Quick Start

### Online (OneCompiler)
1. Open [OneCompiler HTML Editor](https://onecompiler.com/html)
2. Paste the complete Naix Animated code
3. Click **Run**
4. Start animating!

### Offline (Download)
1. Download `index.html` from the repository
2. Double-click to open in any modern browser
3. No internet connection required

### Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `N` | Add new frame |
| `←` | Previous frame |
| `→` | Next frame |
| `Space` | Play / Stop animation |
| `Delete` | Delete current frame |
| `Ctrl + S` | Save project |
| `Ctrl + E` | Export video |

---

## 📁 File Format

Naix Animated saves projects as `.naix` files (JSON-based):

```json
{
  "version": "1.0",
  "name": "Naix Animation",
  "width": 740,
  "height": 480,
  "fps": 12,
  "frames": [
    { "data": [255, 255, 255, 255, ...] }
  ]
}
