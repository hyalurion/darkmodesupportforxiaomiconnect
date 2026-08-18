# Xiaomi Hyper Connect - ダークモード対応

[简体中文](README.md) | [繁體中文](README-zh-Hant.md) | [English](README-en.md) 

このプロジェクトは、PC 版の「Xiaomi Hyper Connect」にダークモード対応を追加するものです。また、Windows のシステム フォント設定に追従することもできます。

> 現在対応しているアプリのバージョンは 2.0.0.438 です。別のアプリ バージョンに置き換えようとしないでください。機能が正常に動作しなくなる可能性があります。

## 有効化方法

1. このプロジェクト内の [app.asar](app.asar) をダウンロードします。
2. 次の場所に置き換えます：`C:\Program Files\MI\HyperConnect\2.0.0.438\resources\app.asar`（Windows）

## 説明

- このプロジェクトには、完全なホットスワップ対応のダークモード適応が含まれており、現在のシステムテーマ設定を検出して自動的に追従します。
- アプリのテーマ状態を切り替えるには、次の場所へ移動してください：設定 - 個人設定 - 色 - モードの選択（Windows）
- Windows ユーザーで、日没時刻やカスタム時刻に基づいてシステムテーマを自動的に切り替えたい場合は、以下のツールをおすすめします：
  - [Microsoft PowerToys Light Switch](https://apps.microsoft.com/detail/XP89DCGQ3K6VLD)
  - [Auto Dark Mode](https://apps.microsoft.com/detail/XP8JK4HZBVF435)
- Windows ユーザーで、レジストリを変更してグローバル システム フォントを変更したい場合（非常に危険な操作）は、次のツールをおすすめします：
  - [noMeiryoUI](https://github.com/Tatsu-syo/noMeiryoUI/releases)

## プレビュー

|  |  |  |  |
| --- | --- | --- | --- |
| ![pic01.png](pic01.png) | ![pic02.png](pic02.png) | ![pic03.png](pic03.png) | ![pic04.png](pic04.png) |
| ![pic05.png](pic05.png) | ![pic06.png](pic06.png) | ![pic07.png](pic07.png) | ![pic08.png](pic08.png) |
