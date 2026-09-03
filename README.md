# Wallpaper Engine

**Wallpaper Engine** free desktop build - live wallpaper, audio visualizer, workshop-style library for Windows 10/11. 4K video, anime, RGB sync (Razer / iCUE / Hue), multi-monitor. Steam optional; this zip is the desktop app.

<img width="800" height="250" alt="images1" src="https://github.com/user-attachments/assets/bb1d8bcf-5cc1-4f6e-a83d-f8fd49987591" />


Unpack, run. Windows 10/11. Import workshop-format packs or drop MP4 / HTML into the library folder.

<img width="1280" height="720" alt="images3" src="https://github.com/user-attachments/assets/acc77fdd-04dd-45ae-9e80-2dc01503c40b" />
<img width="736" height="414" alt="images4" src="https://github.com/user-attachments/assets/fb2ed17e-7c24-4af4-9b3c-f31ff79328ff" />
<img width="1920" height="1080" alt="images5" src="https://github.com/user-attachments/assets/e0df09f4-550b-490b-87b2-927d342d55cd" />
<img width="1500" height="844" alt="images6" src="https://github.com/user-attachments/assets/cbcd109c-effb-47c9-9b0f-506a1f0b6a6d" />

## What's new in v2.8.43 (September 3, 2026)
- Renderer security pass
- Multi-monitor display map fix
- GPU usage limiter tuning
- Workshop import refresh

## Key Features
- 4K video wallpapers
- HTML / web wallpapers
- Audio-reactive scenes
- Anime packs in workshop format
- Multi-monitor span or per-display
- RGB sync: Razer Chroma, iCUE, Hue
- Performance cap and battery pause
- Start with Windows

<img width="565" height="353" alt="images7" src="https://github.com/user-attachments/assets/44a13839-1113-4f7e-a430-0a4abc68f1aa" />

## Config (headers/Config.h)

| Key | Default | Means |
|---|---|---|
| `m_runOnStartup` | true | Start with Windows |
| `m_pauseOnFullscreen` | true | Pause when a game is fullscreen |
| `m_rgbChroma` / `m_rgbICue` / `m_rgbHue` | false | Razer / iCUE / Hue |
| `m_hdrEnabled` | false | HDR |
| `m_qualityLevel` | 2 | Quality |
| `m_maxFPS` | 60 | Cap |
| `m_cacheSizeMB` | 2048 | Cache |
| `m_gpuUsageLimit` | 30 | GPU % |
| `m_pauseOnBattery` | false | Laptop |

<img width="739" height="415" alt="images8" src="https://github.com/user-attachments/assets/500dbea2-f6ea-4d0e-a2a6-0b638d2278df" />

## Troubleshooting

| Symptom | Cause |
|---|---|
| Second display black | MultiMonitor lost HWND - re-apply display map |
| GPU hot | Raise `m_gpuUsageLimit` / drop quality |
| No audio react | Visualizer not bound to the device |
| RGB dead | Chroma / iCUE / Hue flags off |

<img width="800" height="250" alt="images9" src="https://github.com/user-attachments/assets/602fc66b-f281-4499-905f-15c91c54b578" />

## Requirements
Windows 10/11. Steam optional.

## License
MIT notes - Copyright (C) 2026 SteamWallpaperENGINE
