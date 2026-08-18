# 小米互联服务 - 深色模式支持

[繁體中文](README-zh-Hant.md) | [English](README-en.md) | [日本語](README-ja.md)

这是一个为 PC 版「小米互联服务」提供深色模式支持的项目。同时支持跟随Windows系统注册表字体设置。

> 当前适配的应用版本为 2.0.0.438。请勿尝试替换至不同的应用版本，否则将导致功能异常。

## 启用方法

1. 下载项目中的文件 [app.asar](app.asar)
2. 将其替换到：`C:\Program Files\MI\HyperConnect\2.0.0.438\resources\app.asar`（Windows）

## 说明

- 此项目包含完整的热切换深色模式适配支持，能够检测系统当前主题设置并自动跟随。
- 要切换应用的主题状态，请前往：设置 - 个性化 - 颜色 - 选择模式（Windows）
- 对于 Windows 用户，如需根据日落时间或自定义时间自动切换系统主题，建议使用：
  - [Microsoft PowerToys Light Switch](https://apps.microsoft.com/detail/XP89DCGQ3K6VLD)
  - [Auto Dark Mode](https://apps.microsoft.com/detail/XP8JK4HZBVF435)
- 对于 Windows 用户，如需修改您的注册表实现全局系统字体修改（高风险操作），建议使用：
  - [noMeiryoUI](https://github.com/Tatsu-syo/noMeiryoUI/releases)

## 效果预览

|  |  |  |  |
| --- | --- | --- | --- |
| ![pic01.png](pic01.png) | ![pic02.png](pic02.png) | ![pic03.png](pic03.png) | ![pic04.png](pic04.png) |
| ![pic05.png](pic05.png) | ![pic06.png](pic06.png) | ![pic07.png](pic07.png) | ![pic08.png](pic08.png) |