
# XinHuanNewTab

<p align="center">
  <img src="https://xinhuan-hs.github.io/XinHuanNewTab/ico32.ico" alt="Logo" width="64">
</p>

<p align="center">
  一款极简、美观的多引擎搜索新标签页扩展（支持 Chrome / Edge）
</p>

<p align="center">
  <a href="https://xinhuan-hs.github.io/XinHuanNewTab/"><strong>🌐 在线预览 Live Demo »</strong></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Manifest-V3-blue?style=flat-square&logo=googlechrome">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square">
</p>

---

## ✨ 功能特性

*   **🚀 多引擎切换**：内置 Google、Bing、百度、DuckDuckGo、GitHub、知乎六大搜索引擎。
*   **🧠 记忆偏好**：自动保存您上次选择的搜索引擎（基于 `localStorage`）。
*   **🌓 自适应主题**：完美适配浅色/深色模式，自动跟随系统设置。
*   **💎 精致 UI**：采用毛玻璃（Glassmorphism）设计语言，圆润胶囊形态，视觉舒适。
*   **⌨️ 键盘友好**：打开即聚焦，回车即搜索，结果在新标签页打开。
*   **⚡️ 轻量无依赖**：纯原生 HTML/CSS/JS，无需构建工具，毫秒级加载。

---

## 📸 预览效果

| 浅色模式 (Light) | 深色模式 (Dark) |
| :---: | :---: |
| <img src="https://via.placeholder.com/400x250/f5f7fa/1e293b?text=Light+Mode" alt="Light Mode"> | <img src="https://via.placeholder.com/400x250/0f1117/e2e8f0?text=Dark+Mode" alt="Dark Mode"> |

*(提示：你可以将上面的占位图替换为实际的截图)*

---

## 📂 项目结构


XinHuanNewTab/
├── manifest.json      # 扩展配置清单 (Manifest V3)
├── index.html         # 主页面结构
├── style.css          # 样式与主题变量
├── main.js            # 核心逻辑 (搜索、切换、存储)
├── background.js      # 后台服务脚本
├── ico16.ico          # 图标 16x16
├── ico32.ico          # 图标 32x32
├── ico48.ico          # 图标 48x48
└── ico128.ico         # 图标 128x128


---

## 🛠️ 技术栈

*   **Manifest V3**: 最新的 Chrome 扩展标准。
*   **CSS Variables**: 实现动态换色与暗黑模式。
*   **Backdrop Filter**: 实现毛玻璃特效。
*   **Vanilla JavaScript**: 无框架依赖，逻辑清晰。

---

## 🚀 安装与使用

### 作为浏览器扩展安装

1.  **下载代码**  
    克隆仓库或下载 ZIP 并解压：
    bash
    git clone https://github.com/XinHuan-HS/XinHuanNewTab.git


2.  **打开浏览器扩展管理**  
    *   **Chrome**: 访问 `chrome://extensions/`
    *   **Edge**: 访问 `edge://extensions/`

3.  **启用开发者模式**  
    在页面右上角打开“开发者模式”开关。

4.  **加载扩展**  
    点击“加载已解压的扩展程序”，选择 `XinHuanNewTab` 文件夹。

5.  **完成**  
    打开一个新的标签页，享受全新的搜索体验吧！ 🎉

---

## 📖 使用指南

1.  **搜索**：在输入框中输入关键词，按下 `Enter` 键。
2.  **切换引擎**：点击左侧的放大镜图标或引擎名称，选择你想要使用的搜索引擎。
3.  **关闭面板**：点击页面空白处或再次点击左侧图标即可收起引擎列表。

---

## 📜 许可证

本项目基于 [MIT License](https://opensource.org/licenses/MIT) 开源。

---

<p align="center">
  Made with ❤️ by XinHuan
</p>

