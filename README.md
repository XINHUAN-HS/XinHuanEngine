XinHuanNewTab

简洁多引擎搜索 · 新标签页扩展（支持 Chrome / Edge）

https://img.shields.io/badge/Manifest-V3-blue](https://developer.chrome.com/docs/extensions/mv3/)
https://img.shields.io/badge/Demo-Online-brightgreen](https://xinhuan-hs.github.io/XinHuanNewTab/)

打开新标签页，聚焦搜索，一键切换六大搜索引擎，毛玻璃质感 UI 自动跟随系统明暗主题。

🔗 在线预览：https://xinhuan-hs.github.io/XinHuanNewTab/

✨ 特性

• 🔍 六引擎秒切 — Google / Bing / 百度 / DuckDuckGo / GitHub / 知乎

• 💾 偏好记忆 — localStorage 记住你上次选择的引擎

• 🌓 系统主题跟随 — 亮色 / 暗色自动适配（prefers-color-scheme）

• 🎨 毛玻璃 UI — backdrop-filter 半透明输入框 + 圆角胶囊设计

• ⌨️ 键盘友好 — 输入即搜，Enter 新标签打开结果

• 🪶 零依赖 — 纯 HTML / CSS / JS，无构建步骤，即装即用

• 🦊 双内核兼容 — Chrome + Edge（Manifest V3 chrome_url_overrides.newtab）

🌐 支持的搜索引擎

引擎 关键字 搜索地址

Google google google.com/search

Bing bing bing.com/search

百度 baidu baidu.com/s

DuckDuckGo duckduckgo duckduckgo.com

GitHub github github.com/search

知乎 zhihu zhihu.com/search

🛠 技术栈

• Manifest V3 — chrome_url_overrides.newtab 覆盖默认新标签页

• HTML5 + CSS Variables — 明暗主题变量化

• Vanilla JS — 引擎切换、键盘事件、localStorage 持久化

• SVG Icon — 内联放大镜图标，零请求

📁 文件结构


XinHuanNewTab/
├── manifest.json      # 扩展清单（MV3）
├── index.html         # 新标签页入口
├── style.css          # 样式 + CSS 变量主题
├── main.js            # 引擎配置、搜索逻辑、交互
├── background.js      # Service Worker（安装日志）
├── ico16.ico          # 16px 图标
├── ico32.ico          # 32px 图标
├── ico48.ico          # 48px 图标
└── ico128.ico         # 128px 图标


🚀 安装方式

Chrome

1. 下载本仓库 ZIP 并解压，或 git clone
2. 地址栏访问 chrome://extensions/
3. 右上角开启 开发者模式
4. 点击 加载已解压的扩展程序，选择项目文件夹
5. 新建标签页即可看到 XinHuanNewTab

Edge

1. 地址栏访问 edge://extensions/
2. 开启左下角 开发人员模式
3. 点击 加载解压缩的扩展，选择项目文件夹

⚠️ 若同时安装了其他"新标签页"类扩展，Chrome/Edge 只会采用最后启用的那一个。

🎯 使用说明

1. 打开新标签页，光标自动聚焦搜索框
2. 切换引擎：点击左侧放大镜 + 引擎名，弹出六个按钮，点选即切
3. 搜索：输入关键词，按 Enter，结果在新标签页打开
4. 关闭面板：点击引擎选择器外部或再次点击左侧图标
5. 下次打开自动恢复上次使用的引擎

📸 截图

建议在仓库根目录放 screenshot.png（亮色）+ screenshot-dark.png（暗色），并取消下面注释：

<!-- ![Light](screenshot.png) -->
<!-- ![Dark](screenshot-dark.png) -->


📝 许可

MIT © XinHuan

项目主页：https://xinhuan-hs.github.io/XinHuanNewTab/ · 反馈 / PR 欢迎 🌟