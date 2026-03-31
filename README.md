# Dry Fire Target Scaler

A browser-based tool for visualizing shooting targets at realistic distances directly on your monitor.

This app scales and positions targets so they appear as if they are located at real-world distances, based on your screen size, resolution, and viewing distance.

---

## 🎯 Features

- Add multiple targets dynamically
- Support for different target types:
  - USPSA
  - IPSC
  - IDPA
  - Steel
- Target variations:
  - Full size
  - Partial
  - Head-only
  - No-shoot overlays
- Independent distance setting per target
- Realistic scaling based on angular size
- Multiple target spacing modes:
  - Equal spacing (screen-based)
  - Custom real-world spacing (inches)
- Accurate lateral positioning using geometry
- Live updates as you adjust inputs

---

## 📐 How It Works

The app uses real-world geometry to simulate how targets appear at distance.

For each target:
- Angular size is computed from its real-world size and distance
- That angle is projected onto your screen based on your viewing distance
- The result is converted into pixels using your monitor's PPI

For multiple targets:
- Real-world spacing is converted into angular offsets
- Each target is positioned based on its own depth (distance)
- The full array is centered on the screen

---

## ⚙️ Inputs

### Screen Calibration
- Distance from your eyes to the screen (inches)
- Monitor size (diagonal inches)
- Screen resolution (width × height)

### Target Controls
- Add/remove targets
- Select target shape
- Select target type
- Set distance (yards)

### Target Spacing (only appears with 2+ targets)
- Equal spacing on screen
- Custom spacing between adjacent targets (inches)

---

## 🚨 Accuracy Notes

For best results:
- Set your browser zoom to **100%**
- Enter correct monitor size and resolution
- Measure your viewing distance carefully
- Use full-screen mode if possible

Accuracy depends heavily on correct calibration.

---

## 🖥️ Usage

This app runs entirely in the browser—no installation required.

To use:
1. Open the hosted site  
2. Enter your screen calibration values  
3. Add targets  
4. Adjust distances and spacing  
5. Dry fire

---

## 📁 Project Structure
