# X-Plane 12 机场地形平整工具（Simple Flatten 1）

## 🛫 简介  
本工具专为 X-Plane 12 用户设计，以最快速的方法平整机场，用于解决：

1.在使用自动地景或者其他会改变高程数据的插件时可能会导致的地形起伏问题

2.因移除 “跑道随地形起伏” 选项而导致的某些默认机场地形问题

3.其他第三方地景或者插件可能导致的apt.dat损坏

4.小众机场的高程数据错误或者缺失

它会自动分析并且编辑 `apt.dat` 文件，批量添加/移除 `1302 flatten 1` 指令，以实现机场地形的平整化管理。

---

## 版本更新内容

Beta_v0.1.7:
- 优化了用户提示
- 修复了用户使用编号选择单个机场造成的格式错误问题


---

## 🔧 使用场景  
- 修复 X-Plane 12 默认机场的地形错误  
- 快速管理中国、美国等特定区域机场的地形平整状态  
- 修复部分插件造成的机场地形异常  
- 为不熟悉地形编辑专业工具的用户提供最简单的使用方式

---

## ⚠️ 注意事项  
- 本工具**仅修改** `apt.dat` 文件  
- 使用前请务必**备份原始的 X-Plane 12 文件**  
- 当前版本为命令行界面（CLI），**支持简体中文和英文**两种语言
- 本软件仅提供最简单粗暴的平整模式，如须还原最真实的地形请移步XP地形高程数据编辑软件（MUXP）

---

## 💬 意见反馈  
如需提出新功能建议或报告 Bug，欢迎在 GitHub 项目页留言或前往 https://forums.x-plane.org 论坛参与讨论。

---

**——Starlux531**



# X-Plane 12 Airport Terrain Flattening Tool (Simple Flatten 1)

## Update

Beta v0.1.7 updates include:
- Optimized user prompts
- Fixed program crash when users select a single airport with a number
- Updated English version

## 🛫 Introduction  
This tool is specially designed for X-Plane 12 users to address:

1. Terrain bumps caused by automatic scenery or plugins that alter elevation data  
2. Airport terrain errors resulting from disabling the “Runways follow terrain contours” option  
3. Damage to `apt.dat` caused by certain third-party scenery or plugins  
4. Elevation data errors or absence in small or lesser-known airports

It automatically analyzes and edits the `apt.dat` file, batch adding or removing the `1302 flatten 1` command to manage airport terrain flattening.

---

## 🔧 Use Cases  
- Fix terrain bugs in default X-Plane 12 airports  
- Quickly manage airport flattening in regions such as China and the USA  
- Resolve terrain errors caused by third-party plugins or scenery  
- Provide a simple, beginner-friendly solution for users unfamiliar with advanced terrain editing tools

---

## ⚠️ Important Notes  
- This tool **only modifies** the `apt.dat` file  
- Please **back up your original X-Plane 12 files** before use  
- The current version is CLI-based and **supports both Simplified Chinese and English**  
- This software provides only the simplest "brute-force" flattening; for realistic terrain restoration, consider using a dedicated tool like MUXP

---

## 💬 Feedback & Suggestions  
To suggest features or report bugs, feel free to leave a message on the GitHub project page or join the discussion on the https://forums.x-plane.org Forum

---

--Starlux 531--
