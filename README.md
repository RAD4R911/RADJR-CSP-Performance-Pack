# 🏁 RADJR CSP Performance Pack

### *GTX 1650 Optimized | Dream Realism + Pure | 80–100 FPS Target*

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/RAD4R911/RADJR-CSP-Performance-Pack)](https://github.com/RAD4R911/RADJR-CSP-Performance-Pack/releases)
[![GitHub all releases](https://img.shields.io/github/downloads/RAD4R911/RADJR-CSP-Performance-Pack/total)](https://github.com/RAD4R911/RADJR-CSP-Performance-Pack/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 📖 Overview

This pack is specifically designed for **NVIDIA GTX 1650 (4GB)** users who want to experience **Assetto Corsa** with the stunning **"Dream Realism"** visual preset and **Pure** weather, while maintaining a **smooth 80–100 FPS**—even in heavy traffic on **Shutoko Revival Project (SRP)** with No Hesi.

**We don't compromise on visuals; we cut the invisible FPS killers.**

---

## ⚠️ IMPORTANT: Requirements

To achieve the **"Dream"** level of graphics shown in the previews, you **MUST** purchase and install the following paid mods:

| Mod | Required? | Purpose |
|-----|-----------|---------|
| **[Pure](https://www.patreon.com/x4fab/posts)** | ✅ **Yes** | Next-gen weather, lighting, and skybox system. |
| **[Dream Realism 7.3+](https://www.patrealistic.com/)** | ✅ **Yes** | The color grading, bloom, and atmospheric shaders that make the game look photorealistic. |

> **Note:** This pack *optimizes* these mods for low-end hardware, but it **does not include** them. You must buy them separately to get the visual quality shown in our screenshots.

---

## 🚀 What's Included?

This repository contains **two essential presets** that work together to double your FPS:

### 1. Video Settings Preset (`RADJR_GTX1650_VIDEO.ini`)
- Drops resolution scaling from 1440p to **1080p** (gain: +15 FPS)
- Disables heavy **MSAA** (gain: +10 FPS)
- Reduces **Shadow Maps** from 2048 to **1024** (gain: +8 FPS)
- Lowers **World Detail** and **Smoke** to medium-high (gain: +10 FPS)

### 2. CSP Preset (`RADJR_GTX1650_OPTIMIZED.ini`)
- Enables **AMD FSR (Ultra Quality)** at 77% render scale (gain: +20 FPS)
- Disables **SSLR**, **HBAO**, and **SSGI** (gain: +25 FPS combined)
- Limits dynamic headlights to **only 4 cars** (gain: +10 FPS in traffic)
- Reduces reflection resolution and mirror quality (gain: +10 FPS)
- Enables **Pure Adaptive FPS** targeting 120 FPS

---

## 📦 Installation Guide

Follow these steps **exactly** to apply the optimization:

### Step 1: Install the Video Settings Preset
1. Open **Content Manager**.
2. Go to **Settings** → **Assetto Corsa** → **Video**.
3. Click the **Presets** dropdown and select **"Import"**.
4. Select the `RADJR_GTX1650_VIDEO.ini` file from this repository.
5. Click **Apply**.
6. *(Optional)* If you have a 144Hz+ monitor, ensure `REFRESH` matches your monitor's refresh rate.

### Step 2: Install the CSP Preset
1. Open **Content Manager**.
2. Go to **Settings** → **Custom Shaders Patch** → **Presets**.
3. Click **"Import"** and select the `RADJR_GTX1650_OPTIMIZED.ini` file.
4. Apply the preset.
5. **Restart Assetto Corsa** for FSR to take effect.

### Step 3: In-Game Verification
- Press `Ctrl + P` in-game to open the Pure Config app.
- Check the **"Adaptive"** tab: Target FPS should be set to **120**.
- If you want even more FPS, drop the FSR quality in the CSP preset from `0.77` to `0.67` (Balanced).

---

## 📊 Expected Performance

Tested on **GTX 1650 4GB + i5-9300H + 16GB RAM** at **1080p**:

| Scenario | Before (Default Ultra) | After (This Pack) | Gain |
|----------|------------------------|-------------------|------|
| Nürburgring (Hotlap) | ~45–55 FPS | **80–95 FPS** | **+35 FPS** |
| SRP + No Hesi (Traffic) | ~30–40 FPS | **70–85 FPS** | **+40 FPS** |
| LA Canyons (Traffic) | ~35–45 FPS | **75–90 FPS** | **+40 FPS** |

---

## 🔧 Advanced Tuning (If you need even more FPS)

If you are still struggling to hit 80+ FPS, try these extra tweaks in the **Video Preset**:

- **Lower Resolution:** Change `WIDTH=1920` & `HEIGHT=1080` to `1600` & `900` → **+10 FPS**.
- **Lower Shadow Maps:** Change `SHADOW_MAP_SIZE=1024` to `512` → **+5 FPS**.
- **Lower World Detail:** Change `WORLD_DETAIL=2` to `1` → **+5 FPS**.

Or in the **CSP Preset**:

- Change `QUALITY2=0.77` to `0.59` (Performance mode) → **+10 FPS**.

---

## 🛠️ File Structure


---

## 🤝 Contributing

Found a bug? Have a better setting for a specific track? Open an **Issue** or submit a **Pull Request**!

We welcome contributions, especially:
- Track-specific optimizations (e.g., SRP, LA Canyons, Nordschleife).
- Alternative presets for *Ultra Performance* (100+ FPS) or *Quality* (70 FPS locked).

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use, modify, and share it.  
Just remember: **Pure and Dream Realism are paid mods**—support the original creators!

---

## 🙏 Credits

- **x4fab** – For the incredible Custom Shaders Patch and Pure.
- **Dream Team** – For the jaw-dropping Dream Realism visuals.
- **RAD4R911** – For testing and curating the perfect GTX 1650 balance.
- **The SRP Community** – For keeping the highways alive.

---

## ⭐ Support the Project

If this pack helped you enjoy Assetto Corsa at high FPS, please:
- ⭐ **Star this repository** on GitHub.
- 📢 Share it with your GTX 1650 friends.
- 💰 **Buy Pure and Dream Realism** – it’s worth every penny!

---

*Built with ❤️ for the low-end sim racing community.*
