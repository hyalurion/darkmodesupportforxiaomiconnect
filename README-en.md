# Xiaomi Hyper Connect - Dark Mode Support

[简体中文](README.md) | [繁體中文](README-zh-Hant.md) | [日本語](README-ja.md)

This project adds dark mode support for the PC version of Xiaomi Hyper Connect and also supports following the Windows system font settings.

> The currently supported application version is 2.0.0.438. Do not attempt to replace it with a different app version, or the functionality may break.

## Enable

1. Download [app.asar](app.asar) from this project.
2. Replace it at: `C:\Program Files\MI\HyperConnect\2.0.0.438\resources\app.asar` (Windows)

## Notes

- This project includes full hot-swappable dark mode support and can detect the current system theme setting and follow it automatically.
- To switch the app theme state, go to: Settings - Personalization - Colors - Choose your mode (Windows)
- For Windows users who want to automatically switch the system theme based on sunset time or custom times, we recommend:
  - [Microsoft PowerToys Light Switch](https://apps.microsoft.com/detail/XP89DCGQ3K6VLD)
  - [Auto Dark Mode](https://apps.microsoft.com/detail/XP8JK4HZBVF435)
- For Windows users who want to modify the registry to change the global system font (high-risk operation), we recommend:
  - [noMeiryoUI](https://github.com/Tatsu-syo/noMeiryoUI/releases)

## Preview

|  |  |  |  |
| --- | --- | --- | --- |
| ![pic01.png](pic01.png) | ![pic02.png](pic02.png) | ![pic03.png](pic03.png) | ![pic04.png](pic04.png) |
| ![pic05.png](pic05.png) | ![pic06.png](pic06.png) | ![pic07.png](pic07.png) | ![pic08.png](pic08.png) |