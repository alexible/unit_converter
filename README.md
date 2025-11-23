# unit_converter
small app for unit converters. Can be used as PWA

## Installation Guide

## Files Included

1. **unit-converter.html** - Main application file
2. **manifest.json** - PWA configuration
3. **service-worker.js** - Offline functionality
4. **icon-192.png** - App icon (192x192)
5. **icon-512.png** - App icon (512x512)

## How to Install on Android

### Method 1: Using GitHub Pages (Recommended)

1. **Upload all 5 files** to the same directory on GitHub
2. **Enable GitHub Pages** in repository settings
3. **Open your GitHub Pages URL** in Chrome on Android
4. **Wait for install prompt** or tap menu (⋮) → "Install app"
5. **Tap "Install"** - it will add to home screen

### Method 2: Local Testing

1. **Download all 5 files** to your phone
2. **Open unit-converter.html** in Chrome
3. Chrome will show "Add to Home Screen" option
4. Note: Full PWA features require HTTPS (use GitHub Pages for best experience)

## ✅ Successful Installation Indicators

- Opens as **standalone app** (no browser UI)
- **Custom icon** appears on home screen
- Works **offline** after first load
- No Chrome badge if properly installed as WebAPK

## Troubleshooting

### If you see Chrome badge on icon:
- Make sure all 5 files are in the same directory
- Clear Chrome cache and reinstall
- Ensure you're using HTTPS (GitHub Pages provides this)

### If 404 error when opening:
- Check that manifest.json and PNG files are in same folder as HTML
- Verify file names match exactly (case-sensitive)

### If install prompt doesn't appear:
- Wait 10-20 seconds after opening page
- Check Chrome flags: chrome://flags (enable "WebAPK Install")
- Try Menu (⋮) → "Install app" manually

## Features Included

**Conversion Categories:**
- Weight (lbs/kg, oz/g, tons/tonnes)
- Length (in/cm, ft/m, mi/km, yd/m)
- Temperature (°F/°C, °C/K)
- Volume (gal/L, qt/L, fl oz/ml, pt/L)
- Cooking (cups, tbsp, tsp to ml)
- Speed (mph/km/h, knots/mph)

**PWA Features:**
- Offline functionality
- Install to home screen
- Standalone app experience
- Fast loading
- No internet required after installation

© 2025 Alex K
