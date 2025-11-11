# 🚀 Smart Vocabulary Trainer
### Powered by FSRS Memory Algorithm
### 智能单词学习系统 · 基于 FSRS 智能记忆算法

An intelligent vocabulary learning system based on **FSRS (Free Spaced Repetition Scheduler)**,
designed for efficient English word memorization, adaptive review scheduling, and self-growth tracking.

基于 **FSRS（自由间隔重复调度算法）** 的智能单词学习系统，
旨在帮助你高效记忆英语单词，自动安排复习计划，并记录学习成长。

> 💡 Built with pure **HTML + CSS + JavaScript**, running entirely offline — your private AI vocabulary coach.
> 💡 完全由 **HTML + CSS + JavaScript** 构建，无需网络，离线运行 — 你的私人 AI 背单词教练。

---

## ✨ Core Features | 核心功能

| 🌟 Feature | Description | 功能说明 |
|------------|-------------|-----------|
| 🧠 **FSRS Intelligent Memory Algorithm** | Automatically adjusts review intervals based on your recall performance. | 基于记忆曲线的智能算法，根据答题表现自动调整复习间隔。 |
| 📚 **Multi-Mode Practice** | Supports *English → Chinese*, *Chinese → English*, and *Dictation Mode*. | 支持 **英译中**、**中译英**、**听写模式** 三种学习方式。 |
| 🔁 **Adaptive Review Loop** | Missed words appear more often — no more random guessing. | 错题自动回炉，更科学地强化薄弱词汇。 |
| 🕓 **Spaced Repetition Scheduler** | Plans reviews at the optimal memory timing. | 基于遗忘曲线自动规划最佳复习时间。 |
| ⭐ **Favorite & Difficulty Tracking** | Mark tricky words and monitor their difficulty trend. | 收藏重点词汇，追踪难度成长变化。 |
| 📊 **Progress Dashboard** | View stats like accuracy, streaks, difficulty, and stability. | 学习进度可视化，包括正确率、连对数、稳定性等。 |
| 💾 **Local Data Storage** | All data saved locally (no privacy risk). | 所有数据存储在本地浏览器，无需联网、保护隐私。 |
| 🔊 **Built-in Speech Synthesis** | Listen to pronunciation via native TTS. | 内置语音合成功能，可自动发音，辅助听力与口语训练。 |

---

## 🚀 Quick Start | 快速开始

### 🧩 **Option 1 — Online (Recommended)**
👉 **[Launch Demo (coming soon)](https://jinzhuwang-chi.github.io/Word_learning_tool/)**

> Works offline after first load.
> 书签保存后可离线使用，数据通过 `localStorage` 自动保存。

### 💻 **Option 2 — Local Setup**
1. Clone the repository 克隆项目：
   ```bash
   git clone [https://github.com/jinzhuwang-chi/Word_learning_tool.git](https://github.com/jinzhuwang-chi/Word_learning_tool.git)
   cd Word_learning_tool
   ```

2.  Open `index.html` in your browser 打开 `index.html` 文件即可运行。
      * 无需安装、无需构建，纯前端项目。

-----

### ⚠️ Voice Function Notice | 语音功能提示

🔈 **Important / 重要：**
The voice playback feature works only in **Google Chrome**,
as it uses Chrome’s built-in Speech Synthesis API (`window.speechSynthesis`).

语音播放功能仅支持 **Google Chrome** 浏览器，
因为系统调用了 Chrome 内置的语音合成接口。
若使用其他浏览器，可能无法正常播放发音。

**Browser Compatibility / 浏览器兼容性：**

  * ✅ **Google Chrome** — Fully Supported / 完全支持
  * ⚠️ **Microsoft Edge** — Partial Support / 部分支持
  * ❌ **Safari / Firefox** — Not Supported / 暂不支持

-----

### 🧠 Tech Overview | 技术简介

**Architecture / 架构说明：**

  * Pure front-end app (no backend required)
  * Built with HTML + CSS + Vanilla JavaScript
  * Implements FSRS v4.5 Algorithm
  * Local persistence via `localStorage`

**核心结构说明：**

  * 完全前端架构，无需后端依赖
  * 采用 HTML + CSS + 原生 JavaScript 编写
  * 集成 FSRS v4.5 记忆调度算法
  * 所有学习数据自动保存在浏览器本地存储中

> FSRS dynamically adjusts each word’s "stability" and "difficulty"
> to form a personalized memory curve and reduce forgetting.
>
> FSRS 算法根据用户记忆表现自动调整“稳定度”和“难度”，
> 从而生成个性化的记忆曲线，显著降低遗忘率。

-----

### 🖼️ Interface Preview | 界面展示

| Home / 首页 | Practice / 练习界面 | Completion / 学习总结 |
| :---: | :---: | :---: |
| `|` | \`\` |

*Clean UI with gradient style and full mobile adaptation.*
*渐变色设计，界面简洁美观，完美适配移动端。*

-----

## 🔮 Roadmap | 未来规划

  * [ ] CSV / Anki format import & export （CSV/Anki 格式导入导出）
  * [ ] Voice recognition for dictation mode （语音识别听写模式）
  * [ ] Memory curve & statistics visualization （记忆曲线与学习数据可视化）
  * [ ] PWA support for full offline app experience （PWA 支持，实现完全离线运行）

-----

## 📄 License | 许可协议

MIT License © 2025 JinZhu Wang

> “The secret to remembering is not repeating — it’s repeating smartly.”
> “记忆的秘诀，不是不断重复，而是聪明地重复。”

```
```

