# DayMusic - Support

[English](#english) | [中文](#中文)

---

## English

### 📱 About DayMusic

DayMusic is a local lossless music player designed exclusively for iPhone, delivering Hi-Res audio playback with professional-grade features. All your music data is securely stored locally on your device and optionally in your private iCloud account, never uploaded to any third-party servers.

### ✨ Key Features

- **🎵 Hi-Res Audio Playback** - Support for FLAC, ALAC, WAV, AIFF, APE, DSD, MP3, and AAC formats
- **🎛️ 10-Band Equalizer** - Professional parametric EQ with 7 built-in presets and custom preset saving
- **📊 Real-time Spectrum** - Visualize audio frequencies in real-time, tap to switch between waveform and spectrum views
- **🔍 Lossless Verification** - Multi-dimensional audio analysis to detect fake lossless files (upsampled from lossy)
- **☁️ iCloud Sync** - Automatically sync your music library across devices
- **📋 Smart Queue** - Apple Music-style dual queue with "Play Next" priority queue
- **🎨 Theme Support** - Light, Dark, and System auto-switching themes
- **🌍 Bilingual** - Full English and Chinese language support

### ❓ Frequently Asked Questions

#### What audio formats does DayMusic support?

DayMusic supports 9 audio formats:
- **Lossless (native):** FLAC, ALAC, WAV, AIFF
- **Lossless (FFmpeg):** APE, DSD (DSF/DFF)
- **Lossy:** MP3, AAC

#### How does DayMusic protect my privacy?

All your music files and app data are stored locally on your device. We don't collect, transmit, or store any data on third-party servers. When iCloud sync is enabled, files sync to your private iCloud account only.

#### What does the audio quality detection do?

DayMusic analyzes the frequency spectrum of lossless files to verify they are genuine. It checks:
- Frequency cutoff patterns
- Spectral smoothness (brick-wall detection)
- High-frequency noise floor characteristics
- Multi-segment consistency

Results are labeled as "Genuine," "Suspect," or "Fake."

#### What is Hi-Res audio?

Hi-Res audio refers to lossless files with sample rates above 44.1kHz or bit depths above 16-bit (e.g., 96kHz/24-bit FLAC). DayMusic automatically matches the output sample rate to the source file for bit-perfect playback.

#### How do I import music?

Two methods:
1. **In-app:** Tap the "+" button → Import Music → Select files
2. **iTunes/Finder:** Connect iPhone to computer, open Finder (macOS) or iTunes (Windows), drag music files to DayMusic in the Files tab

#### How does the play queue work?

DayMusic uses an Apple Music-style dual queue:
- **Play Next:** Songs added via long press → "Play Next" are inserted right after the current song
- **Queue:** The original playlist continues after all "Play Next" songs finish

#### How do I delete my data?

- **Delete specific songs:** Long press a song → Delete
- **Delete all data:** Uninstall the app from your device
- **iCloud data:** Manage in Settings → [Your Name] → iCloud → Manage Storage → DayMusic

#### What devices are supported?

DayMusic is designed for iPhone and supports devices running iOS 15.6 or later, including iPhone SE.

### 🔧 Usage Guide

#### How to create a playlist?

Tap the "+" button in the top right corner → New Playlist → Enter a name → Optionally select songs to add.

#### How to use the equalizer?

Open the player view → Tap "EQ" at the bottom → Toggle the equalizer on → Select a preset or adjust individual frequency bands.

#### How to switch between waveform and spectrum?

In the player view, tap the waveform/spectrum area to toggle between the two visualizations.

#### How to enable iCloud sync?

Open Settings (gear icon) → Features → iCloud Sync → Enable the toggle. Make sure your device is logged into your iCloud account.

### 📧 Contact Us

Need help or have suggestions? We'd love to hear from you.

**Developer**: lu yiang
**Email**: [lyi4ng@gmail.com](mailto:lyi4ng@gmail.com)

If you have any questions, suggestions, or need technical support, please feel free to contact us via email.

---

## 中文

### 📱 关于 DayMusic

DayMusic 是一款专为 iPhone 设计的本地无损音乐播放器，提供 Hi-Res 高解析度音频播放体验。所有音乐数据都安全地存储在您的设备本地和私人 iCloud 账户中，绝不会上传到任何第三方服务器。

### ✨ 主要功能

- **🎵 Hi-Res 音频播放** - 支持 FLAC、ALAC、WAV、AIFF、APE、DSD、MP3、AAC 共 9 种格式
- **🎛️ 10 频段均衡器** - 专业参数 EQ，7 个内置预设，支持自定义预设保存
- **📊 实时频谱** - 实时可视化音频频率分布，点击可切换波形图和频谱图
- **🔍 无损鉴定** - 多维度频谱分析，检测伪无损文件（从有损转码而来）
- **☁️ iCloud 同步** - 自动同步音乐库到 iCloud，多设备访问
- **📋 智能队列** - Apple Music 风格双层队列，支持"下一首播放"优先队列
- **🎨 主题支持** - 浅色、深色和跟随系统自动切换
- **🌍 双语支持** - 完整的中英文界面

### ❓ 常见问题

#### DayMusic 支持哪些音频格式？

DayMusic 支持 9 种音频格式：
- **无损（原生支持）：** FLAC、ALAC、WAV、AIFF
- **无损（FFmpeg 解码）：** APE、DSD（DSF/DFF）
- **有损：** MP3、AAC

#### DayMusic 如何保护我的隐私？

您的所有音乐文件和应用数据都存储在设备本地。我们不会收集、传输或存储任何数据到第三方服务器。启用 iCloud 同步后，文件仅同步到您的私人 iCloud 账户。

#### 音质检测功能是什么？

DayMusic 通过分析无损文件的频谱来验证其真实性，检测维度包括：
- 频率截止模式
- 频谱平滑度（砖墙效应检测）
- 高频噪底特征
- 多段一致性

结果标记为"真无损"、"疑似转码"或"伪无损"。

#### 什么是 Hi-Res 音频？

Hi-Res 音频指采样率高于 44.1kHz 或位深高于 16-bit 的无损文件（如 96kHz/24-bit FLAC）。DayMusic 会自动将输出采样率匹配源文件，实现 bit-perfect 播放。

#### 如何导入音乐？

两种方式：
1. **应用内导入：** 点击右上角"+"→ 导入音乐 → 选择文件
2. **iTunes/Finder：** 将 iPhone 连接至电脑，打开 Finder（macOS）或 iTunes（Windows），在"文件"标签页中将音乐文件拖入 DayMusic

#### 播放队列是如何工作的？

DayMusic 使用 Apple Music 风格的双层队列：
- **下一首播放：** 通过长按歌曲 → "下一首播放"插入到当前歌曲之后
- **队列：** 所有"下一首播放"的歌曲播完后，继续播放原始队列

#### 如何删除数据？

- **删除单首歌曲：** 长按歌曲 → 删除
- **删除所有数据：** 从设备卸载应用
- **iCloud 数据：** 在设置 → [您的名字] → iCloud → 管理存储 → DayMusic 中管理

#### 支持哪些设备？

DayMusic 专为 iPhone 设计，支持运行 iOS 15.6 及以上版本的 iPhone，包括 iPhone SE。

### 🔧 使用帮助

#### 如何创建歌单？

点击右上角"+"按钮 → 新建歌单 → 输入名称 → 可选择添加歌曲。

#### 如何使用均衡器？

打开播放详情页 → 点击底部"EQ"→ 开启均衡器 → 选择预设或手动调节各频段。

#### 如何切换波形图和频谱图？

在播放详情页，点击波形/频谱区域即可在两种可视化之间切换。

#### 如何启用 iCloud 同步？

打开设置（齿轮图标）→ 功能 → iCloud 同步 → 开启。确保您的设备已登录 iCloud 账户。

### 📧 联系我们

需要帮助或有建议？我们很乐意听取您的反馈。

**开发者**: lu yiang
**邮箱**: [lyi4ng@gmail.com](mailto:lyi4ng@gmail.com)

如有任何问题、建议或需要技术支持，请随时通过邮箱联系我们。

---

© 2026 DayMusic. All rights reserved.
