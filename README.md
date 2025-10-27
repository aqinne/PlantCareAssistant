# Home-Plant-Care-Assistant- 智能植物养护助手


一个基于 **C++/Qt** 开发的跨平台桌面应用，旨在通过量化管理与智能提醒，解决家庭用户“养不活、记不住”的植物养护痛点。

[![C++](https://img.shields.io/badge/C++-17+-00599C?logo=cplusplus)](https://en.cppreference.com/)
[![Qt](https://img.shields.io/badge/Qt-5.12+-41CD52?logo=qt)](https://www.qt.io/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## ✨ 项目特色

- **🪴 科学养护**：内置常见植物养护数据库，自动计算浇水、施肥周期。
- **⏰ 智能提醒**：基于 `QTimer` 的任务调度系统，准时推送养护任务，支持优先级管理。
- **📊 健康监控**：动态计算植物健康度，通过颜色与图标可视化状态。
- **💾 数据持久化**：使用 `QSettings` 实现配置与植物数据的本地序列化存储，无需外部数据库。
- **🎨 优雅界面**：基于 Qt Widgets 开发的友好图形界面，支持跨平台运行。

## 🗂 项目结构
PlantCareAssistant/
├── main.cpp # 程序入口，应用初始化
├── mainwindow.[h/cpp] # 主窗口界面与用户交互逻辑
├── plantmanager.[h/cpp] # 植物数据管理与健康度计算核心模块
├── carescheduler.[h/cpp] # 养护任务调度与提醒引擎
└── resources/ # 应用图标与界面资源

## 🛠 核心技术栈

- **语言**: C++11
- **框架**: Qt 5 (Widgets, Signals & Slots, Timer, Settings)
- **工具链**: GCC/G++, Make, GDB
- **数据持久化**: QSettings (序列化)
- **开发环境**: Linux/Windows, Qt Creator

## 🚀 编译与运行

### 环境要求
- Qt 5.12 或更高版本
- 支持 C++11 的编译器 (GCC, MSVC等)
