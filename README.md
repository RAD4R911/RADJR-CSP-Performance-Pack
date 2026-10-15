# RADJR CSP Performance Pack

### Assetto Corsa CSP and Content Manager presets for balanced visual quality and performance

[![Latest release](https://img.shields.io/github/v/release/RAD4R911/RADJR-CSP-Performance-Pack)](https://github.com/RAD4R911/RADJR-CSP-Performance-Pack/releases)
[![Downloads](https://img.shields.io/github/downloads/RAD4R911/RADJR-CSP-Performance-Pack/total)](https://github.com/RAD4R911/RADJR-CSP-Performance-Pack/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

The **RADJR CSP Performance Pack** is a curated collection of Custom Shaders Patch and Assetto Corsa Content Manager settings for sim-racing setups that want a strong visual presentation without unnecessarily aggressive GPU settings.

The current package is **v1.0.3**. It is intended for Assetto Corsa users running Content Manager and CSP, with settings suitable as a starting point for 1080p high-refresh-rate displays.

> The presets are starting points, not universal benchmarks. Actual FPS depends on the car, track, traffic, weather, CSP version, Pure configuration, resolution, CPU, GPU, and VR or monitor mode.

## Included in v1.0.3

| File | Purpose |
| --- | --- |
| [`presets/RADJR_CSP_v1.0.3.ini`](presets/RADJR_CSP_v1.0.3.ini) | CSP preset covering general, graphics, lighting, weather, rain, reflections, shadows, tyres, grass, camera, VR, FFB, and other CSP sections. |
| [`presets/RADJR_VIDEO_v1.0.3.cmpreset`](presets/RADJR_VIDEO_v1.0.3.cmpreset) | Content Manager video preset for a 1920×1080 display at 144 Hz. |
| [`releases/RADJR.CSP.Performance.Pack.v1.0.3_rar.rar`](releases/RADJR.CSP.Performance.Pack.v1.0.3_rar.rar) | Original v1.0.3 archive supplied with the package. |

### Video preset highlights

- 1920×1080 fullscreen output at 144 Hz
- 4× anti-aliasing and 16× anisotropic filtering
- 2048 shadow map size
- 1024 high-quality mirrors
- 512 cubemap size
- Smoke rendered in mirrors
- Post-processing enabled with configurable glare, heat shimmer, and god rays
- 144 FPS display refresh target with VSync disabled

## Requirements

- Assetto Corsa
- Content Manager
- A compatible Custom Shaders Patch installation
- A graphics driver that supports the selected CSP features

The pack can be used without Pure or Dream Realism. Those are optional visual mods, not included in this repository, and must be installed separately from their official sources if you choose to use them.

## Installation

### 1. Install the CSP preset

1. Download [`RADJR_CSP_v1.0.3.ini`](presets/RADJR_CSP_v1.0.3.ini).
2. Open Content Manager and go to **Settings → Custom Shaders Patch → Presets**.
3. Use **Import** if available, or copy the file into Content Manager's CSP preset folder.
4. Select the preset and click **Apply**.

### 2. Import the video preset

1. Download [`RADJR_VIDEO_v1.0.3.cmpreset`](presets/RADJR_VIDEO_v1.0.3.cmpreset).
2. In Content Manager, open **Settings → Assetto Corsa → Video**.
3. Open the **Presets** menu and choose **Import**.
4. Select the `.cmpreset` file, apply it, and restart Assetto Corsa if requested.

### 3. Verify in-game

- Confirm that the selected CSP preset is active.
- Confirm that the display resolution and refresh rate match your monitor.
- Check mirrors, weather, lighting, traffic, and rain before joining an online session.
- Adjust reflections, shadows, smoke, and post-processing if your frame time is too high.

## Performance tuning

If you need additional headroom, try one change at a time and measure frame time:

| Adjustment | Typical trade-off |
| --- | --- |
| Reduce shadow map size from 2048 to 1024 | Lower shadow detail; can improve GPU headroom |
| Reduce mirror size from 1024 to 512 | Lower mirror clarity; can improve mirror rendering cost |
| Reduce cubemap size from 512 to 256 | Lower reflection detail |
| Lower smoke quality | Reduced smoke detail and rendering cost |
| Disable heat shimmer, god rays, or extra glare | Fewer post-processing effects |
| Lower world detail or traffic count | Less scene and CPU workload |

Do not assume a quoted FPS number will apply to every system. Use an in-game frame-time overlay and tune for stable performance rather than a short peak FPS reading.

## Compatibility notes

- CSP settings and section names can change between CSP versions. If Content Manager reports an unknown or obsolete setting, update CSP or remove that setting rather than forcing it.
- Pure, weather scripts, traffic, VR, triple-screen rendering, and large online servers may require separate tuning.
- Back up your existing presets before applying a new configuration.

## Contributing

Bug reports and pull requests are welcome. When reporting an issue, include:

- Content Manager and CSP versions
- GPU, CPU, resolution, and display refresh rate
- Track, car, traffic, weather, and Pure configuration
- The setting that caused the issue and any relevant log output

## License

The configuration files in this repository are released under the MIT License. See the repository's license information for details.

Pure, Dream Realism, Custom Shaders Patch, Content Manager, Assetto Corsa, and other third-party products remain the property of their respective creators. This repository does not redistribute those products.
