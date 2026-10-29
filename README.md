# USB2504A USB 2.0 扩展坞方案验证板

基于 USB2504A 的 USB 2.0 扩展坞。每个下游口带独立 TT，多设备同时工作时稳定性好。

## 特点

- 芯片：USB2504A，每个下游口独立 TT，多设备并发稳定
- PCB 尺寸：34.5 × 41 mm，小巧
- 所有元件均使用 0603 / 1206 / 直插封装，PCB 直接丝印元件参数，手工焊接友好
- 带有简易的过流保护
- 所有端口均已做差分线等长
- 上游口：可焊 Type-C 座，也可直接焊数据线
- 下游口：可焊 USB-A 母座，也可直接焊数据线
- 已验证：个人 DIY 打板焊接，工作正常

## 打开工程

使用 **嘉立创 EDA** 打开项目文件 `usb2504a-test.eprj2`。

## 说明

- 本项目为个人 DIY 方案验证，非量产设计，作者不对使用本设计造成的任何损失承担责任。
- 打板前请自行复核供电、过流保护和封装。
- 本板未设计 ESD 器件，建议在你的设计中补充。
- 过流保护较简陋，建议替换为例如 NCP380HSNAJAAT1G。

## 许可证

本项目遵循 GPL-3.0 协议开源。

# USB2504A USB 2.0 Hub — Proof-of-Concept Board

A USB 2.0 hub based on the USB2504A. Each downstream port has its own Transaction Translator (TT), providing stable operation with multiple devices connected simultaneously.

## Features

- Chip: USB2504A, independent TT per downstream port, stable under concurrent load
- PCB size: 34.5 × 41 mm, compact
- All components use 0603 / 1206 / through-hole packages; component values are silkscreened on the PCB for easy hand soldering
- Basic overcurrent protection
- All ports have length-matched differential pairs
- Upstream port: solder a Type-C receptacle, or solder a data cable directly
- Downstream ports: solder USB-A receptacles, or solder data cables directly
- Verified: personally fabricated and assembled, works normally

## Opening the Project

Open `usb2504a-test.eprj2` with **LCEDA (JLCEDA)**.

## Notes

- This is a personal DIY proof-of-concept, not a production design. The author assumes no liability for any loss resulting from the use of this design.
- Please verify power, overcurrent protection, and footprints before fabrication.
- No ESD protection devices are included; add them in your own design.
- The overcurrent protection is rudimentary; consider replacing it with e.g. NCP380HSNAJAAT1G.

## License

This project is released under GPL-3.0.
