# RADJR CSP Performance Pack

Assetto Corsa **Custom Shaders Patch (CSP)** settings and Content Manager presets for balanced 1080p visual quality and performance.

[![Latest release](https://img.shields.io/github/v/release/RAD4R911/RADJR-CSP-Performance-Pack)](https://github.com/RAD4R911/RADJR-CSP-Performance-Pack/releases)
[![Downloads](https://img.shields.io/github/downloads/RAD4R911/RADJR-CSP-Performance-Pack/total)](https://github.com/RAD4R911/RADJR-CSP-Performance-Pack/releases)

## Overview

The RADJR CSP Performance Pack is a curated set of CSP configuration files and Content Manager presets for Assetto Corsa. It is designed as a practical starting point for 1080p users who want improved lighting, weather, reflections, shadows, camera behavior, and other CSP features without targeting extreme hardware.

The current package is **v1.0.3**.

> These are starting-point settings, not guaranteed FPS figures. Performance depends on the CPU, GPU, laptop power limit and thermals, resolution, car, track, traffic, weather, CSP version, Pure configuration, and VR or monitor mode.

## Download v1.0.3

For the easiest installation, download the release archive from GitHub:

**[Download RADJR CSP Performance Pack v1.0.3](https://github.com/RAD4R911/RADJR-CSP-Performance-Pack/releases/tag/v1.0.3)**

The release includes `RADJR.CSP.Performance.Pack.v1.0.3_rar.rar`.

The individual preset files are also available in the repository:

- [`RADJR_CSP_v1.0.3.ini`](presets/RADJR_CSP_v1.0.3.ini) — CSP preset
- [`RADJR_VIDEO_v1.0.3.cmpreset`](presets/RADJR_VIDEO_v1.0.3.cmpreset) — Content Manager video preset

## Hardware targets

| Tier | Target GPU | Recommended approach |
| --- | --- | --- |
| **Minimum** | **GTX 1650 Laptop 4 GB** | Use the preset as a starting point; reduce traffic, mirrors, shadows, smoke, or post-processing if needed. |
| **Mid-range** | **GTX 1660 Super 6 GB** | Balanced 1080p use with moderate traffic and the included settings. |
| **High requirement** | **RTX 3060 12 GB or equivalent** | Higher visual settings, heavier traffic, and more consistent high-refresh-rate performance. |

The GTX 1650 Laptop is the minimum target for this pack. The GTX 1660 Super is the recommended mid-range target, and the RTX 3060 is the high-end target for the included settings. A laptop GPU’s power limit and cooling can significantly affect performance.

## Software requirements

- Assetto Corsa
- Content Manager
- A compatible Custom Shaders Patch installation
- A graphics driver that supports the selected CSP features

Pure and Dream Realism are optional. They are not included in this repository and must be installed separately from their official sources if you choose to use them.

## What is included

### Packaged presets

| File | Purpose |
| --- | --- |
| [`presets/RADJR_CSP_v1.0.3.ini`](presets/RADJR_CSP_v1.0.3.ini) | CSP preset covering general, graphics, lighting, weather, rain, reflections, shadows, tyres, grass, camera, VR, FFB, and other CSP sections. |
| [`presets/RADJR_VIDEO_v1.0.3.cmpreset`](presets/RADJR_VIDEO_v1.0.3.cmpreset) | Content Manager video preset configured for 1920×1080 at 144 Hz. |

### Video preset highlights

- 1920×1080 fullscreen output at 144 Hz
- 4× anti-aliasing and 16× anisotropic filtering
- 2048 shadow map size
- 1024 high-quality mirrors
- 512 cubemap size
- Smoke rendered in mirrors
- Post-processing enabled with glare, heat shimmer, and god-ray options
- VSync disabled

### Individual CSP configuration files

The repository root also contains individual CSP section files such as `rain_fx.ini`, `lighting_fx.ini`, `weather_fx.ini`, `reflections_fx.ini`, `grass_fx.ini`, `shadowed_wheels.ini`, `tyres_fx.ini`, and related configuration and data files. These are provided for users who prefer to inspect or manage CSP sections individually.

The packaged `RADJR_CSP_v1.0.3.ini` preset is the recommended starting point for most users.

## Installation

### Option A: Install from the release archive

1. Download the [v1.0.3 release archive](https://github.com/RAD4R911/RADJR-CSP-Performance-Pack/releases/tag/v1.0.3).
2. Extract the archive with a RAR-compatible extractor.
3. In Content Manager, open **Settings → Custom Shaders Patch → Presets**.
4. Import the included CSP `.ini` preset, select it, and click **Apply**.
5. Open **Settings → Assetto Corsa → Video → Presets**.
6. Import the included `.cmpreset` video preset and click **Apply**.

### Option B: Install the individual repository files

1. Download [`RADJR_CSP_v1.0.3.ini`](presets/RADJR_CSP_v1.0.3.ini) and [`RADJR_VIDEO_v1.0.3.cmpreset`](presets/RADJR_VIDEO_v1.0.3.cmpreset).
2. Import the CSP preset through **Settings → Custom Shaders Patch → Presets**.
3. Import the video preset through **Settings → Assetto Corsa → Video → Presets**.
4. Apply both presets and restart Assetto Corsa if Content Manager requests it.

Always back up your existing Content Manager and CSP presets before applying a new configuration.

## In-game verification

After installation:

- Confirm that the RADJR CSP preset is selected and active.
- Confirm that the display resolution and refresh rate match your monitor.
- Check mirrors, lighting, weather, rain, traffic, and post-processing in a practice session.
- If frame time is too high, lower mirrors, shadows, smoke, reflections, or post-processing first.

## Performance tuning

Change one setting at a time and measure frame time:

| Adjustment | Trade-off |
| --- | --- |
| Reduce shadow map size from 2048 to 1024 | Lower shadow detail and GPU cost |
| Reduce mirror size from 1024 to 512 | Lower mirror clarity and rendering cost |
| Reduce cubemap size from 512 to 256 | Lower reflection detail |
| Lower smoke quality | Less smoke detail and rendering cost |
| Disable heat shimmer, god rays, or extra glare | Fewer post-processing effects |
| Lower world detail or traffic count | Less scene and CPU workload |

Aim for stable frame time rather than a short peak FPS reading.

## Compatibility notes

- CSP settings and section names can change between CSP versions. If Content Manager reports an unknown or obsolete setting, update CSP or remove that setting rather than forcing it.
- Pure, weather scripts, traffic, VR, triple-screen rendering, and large online servers may require separate tuning.
- The included video preset targets 1920×1080 at 144 Hz. Change resolution and refresh-rate values for your own display before driving if necessary.
- Test changes offline before joining an online session.

## Contributing

Bug reports and pull requests are welcome. When reporting an issue, include:

- Content Manager and CSP versions
- GPU, CPU, laptop model and power mode where relevant
- Resolution and display refresh rate
- Track, car, traffic, weather, and Pure configuration
- The setting that caused the issue and any relevant log output

## Third-party software

Assetto Corsa, Content Manager, Custom Shaders Patch, Pure, Dream Realism, and other third-party products remain the property of their respective creators. This repository does not redistribute those products.

This repository currently does not include a license file. Do not assume the configuration files may be redistributed or modified outside the permissions granted by the repository owner.
