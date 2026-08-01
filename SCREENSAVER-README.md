# Liquid Glass Fluid — Screensaver

A self-contained WebGL fluid simulation designed to work as a screensaver.

## Quick start (any OS)

1. Open `liquid-glass-screensaver.html` in Chrome / Edge / Firefox
2. It will automatically request fullscreen
3. Cursor is hidden
4. Continuous gentle colorful flow runs forever
5. **Any mouse move, click, key, or touch exits** (classic screensaver behaviour)

---

## Best ways to use it as a real screensaver

### Windows – easiest & best looking

**Option A – Lively Wallpaper (recommended)**
1. Install [Lively Wallpaper](https://www.rocksdanister.com/lively/) (free)
2. Add → Open file → select `liquid-glass-screensaver.html`
3. Set as wallpaper
4. In Lively settings you can make it pause when full-screen apps are running, etc.

**Option B – Wallpaper Engine** (Steam, paid)
Same idea – add the HTML file as a web wallpaper.

**Option C – True .scr screensaver**
You can turn the HTML into a real Windows screensaver with Electron or WebView2.
A simple ready-made path:

1. Install Node.js
2. Use a minimal Electron template that loads this HTML in fullscreen kiosk mode and quits on any input
3. Rename the built `.exe` to `.scr` and drop it in `C:\Windows\System32`

(I can generate a complete Electron project for this if you want.)

### macOS

1. Open the HTML in Safari or Chrome and go fullscreen (or use the auto-fullscreen version)
2. For a real `.saver` bundle you need Xcode + a WKWebView screensaver plugin – more advanced.

### Just leave it running

Open the file, press F11 (or let it go fullscreen itself), and walk away.  
Any input will exit.

---

## Files

- `liquid-glass-screensaver.html` → the screensaver itself
- `liquid-glass-fluid.html` → the interactive version (drag to paint)

Enjoy the liquid glass.
