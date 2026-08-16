# v1.7.2

---

## ENGLISH

### What's New
DictTango AI Hub brings intelligent AI-powered features to your dictionary:
- **AI ChatBot**: Chat with AI assistants (DeepSeek, Google Gemini, OpenAI, etc.)
- **AI Browser**: Browse web pages while chatting with AI about the content
- **Ask AI**: Right-click text to get AI insights about selected words
- **AI Dictionaries**: Create AI-powered dictionaries that generate definitions on-the-fly
- **Prompt Management**: Save and organize AI prompts for reuse

### Quick Start
1. Go to AI Hub in the main menu
2. Add an AI Service (Services tab) - enter your API details and test
3. Start chatting in ChatBot tab
4. Try AI Browser to browse & chat at the same time
5. Right-click dictionary text to use "Ask AI"

### Key Features
- ✨ Real-time streaming responses
- 🌍 Multiple AI service support
- 📝 Markdown-to-HTML rendering
- 💾 Optional result caching
- 🖥️ Modern clean design
- 🌐 English, Simplified Chinese, Traditional Chinese support

### Requirements
- Windows 10.0.22621.0+
- .NET 10.0
- x64 architecture
- Internet connection for AI services

---

## 简体中文

### 新增功能
DictTango AI 中心为您的字典带来智能 AI 功能：
- **AI 聊天机器人**：与 AI 助手聊天（DeepSeek、Google Gemini、OpenAI 等）
- **AI 浏览器**：边浏览网页边与 AI 聊天页面内容
- **对选中文本提问 AI**：右键点击文本获取 AI 见解
- **AI 字典**：创建 AI 字典，即时生成定义
- **提示词管理**：保存和整理 AI 提示词以供重复使用

### 快速开始
1. 在主菜单中打开 AI 中心
2. 添加 AI 服务（AI 服务选项卡）- 输入 API 信息并测试
3. 在聊天机器人选项卡中开始聊天
4. 尝试 AI 浏览器同时浏览和聊天
5. 右键点击字典文本使用"提问 AI"

### 主要功能
- ✨ 实时流式响应
- 🌍 支持多个 AI 服务
- 📝 Markdown 到 HTML 渲染
- 💾 可选结果缓存
- 🖥️ 现代简洁设计
- 🌐 支持英文、简体中文、繁体中文

### 系统要求
- Windows 10.0.22621.0+
- .NET 10.0
- x64 架构
- 需要网络连接以调用 AI 服务

---

## 繁體中文

### 新增功能
DictTango AI 中心為您的字典帶來智能 AI 功能：
- **AI 聊天機器人**：與 AI 助手聊天（DeepSeek、Google Gemini、OpenAI 等）
- **AI 瀏覽器**：邊瀏覽網頁邊與 AI 聊天頁面內容
- **對選中文字提問 AI**：右鍵點擊文字獲取 AI 見解
- **AI 字典**：建立 AI 字典，即時產生定義
- **提示詞管理**：儲存和整理 AI 提示詞以供重複使用

### 快速開始
1. 在主功能表中開啟 AI 中心
2. 新增 AI 服務（AI 服務索引標籤）- 輸入 API 資訊並測試
3. 在聊天機器人索引標籤中開始聊天
4. 嘗試 AI 瀏覽器同時瀏覽和聊天
5. 右鍵點擊字典文字使用「提問 AI」

### 主要功能
- ✨ 即時串流響應
- 🌍 支援多個 AI 服務
- 📝 Markdown 到 HTML 呈現
- 💾 可選結果快取
- 🖥️ 現代簡潔設計
- 🌐 支援英文、簡體中文、繁體中文

### 系統要求
- Windows 10.0.22621.0+
- .NET 10.0
- x64 架構
- 需要網路連線以呼叫 AI 服務

# v1.7.0

### **English**

1. Fixed display issues related to dark mode adaptation on Windows systems.

---

**Simplified Chinese（简体中文）**
1. 修复了 Windows 系统暗黑模式适配下的显示异常问题
   
---
### **Traditional Chinese (繁體中文)**

1. 修復了 Windows 系統暗黑模式適配下的顯示異常問題。
   
v1.6.9

### **English**

1. Fixed display issues related to dark mode adaptation on Windows systems.

---

**Simplified Chinese（简体中文）**
1. 修复了 Windows 系统暗黑模式适配下的显示异常问题
   
---
### **Traditional Chinese (繁體中文)**

1. 修復了 Windows 系統暗黑模式適配下的顯示異常問題。

v1.6.6.0

### **English**

1. Upgrade WinUI components to version 2.0
2. Reduce memory usage during standard dictionary lookups
3. Update the Edge version number for TTS

---

**Simplified Chinese（简体中文）**
1. 升级WinUI组件到2.0
2. 减少普通查词时的内存占用
3. 更新TTS的Edge版本号
   
---
### **Traditional Chinese (繁體中文)**

1. 將 WinUI 元件升級至 2.0
2. 降低一般查詞時的記憶體使用量
3. 更新 TTS 的 Edge 版本號

---

If you want a more formal, release-note style or UI-friendly phrasing, I can refine it further.


更新到 .NET 10

# v1.6.0.0

Update runtime to .net 10

Here are the translations:

**Simplified Chinese（简体中文）**

* 更新到 .NET 10

**Traditional Chinese（繁體中文）**

* 更新到 .NET 10


# v1.5.1.0

1. Fixed an issue where dictionary files could not be copied when opening DictTango
2. Fixed an issue where the dictionary did not jump correctly in reading mode if it was not in the current group
3. Added global CSS file support

   * File name should be `global.css` or `global_<theme>.css`, placed under `C:\ProgramData\JimexStudio\DictTango\UserAssets`
   * Theme-specific CSS loads first; if not found, fallback to `global.css`.
     Example: if the current theme is dark mode, the app will look for `global_dark.css`; if not found, it will load `global.css`.

---

## 简体中文

1. 修正了打开 DictTango 时，词典文件不能复制的问题
2. 修复了阅读模式下词典不在当前分组时的跳转问题
3. 添加全局 CSS 文件功能

   * 文件名为 `global.css` 或 `global_<主题>.css`，放在 `C:\ProgramData\JimexStudio\DictTango\UserAssets`
   * 主题相关的 CSS 会优先加载，如果没有，则加载 `global.css`。
     例如当前主题为暗黑模式，会优先寻找 `global_dark.css`；如果找不到，则加载 `global.css`。

---

## 繁體中文

1. 修正了開啟 DictTango 時，詞典檔案無法複製的問題
2. 修復了閱讀模式下詞典不在當前分組時的跳轉問題
3. 添加全域 CSS 檔案功能

   * 檔名為 `global.css` 或 `global_<theme>.css`，放在 `C:\ProgramData\JimexStudio\DictTango\UserAssets`
   * 主題相關的 CSS 會優先載入，若找不到，則載入 `global.css`。
     例如當前主題為暗黑模式，會優先尋找 `global_dark.css`；若找不到，則載入 `global.css`。


# 1.5.0
日期: 2025年07月22日
- 添加了高透光亚克力材质
- 修复了鼠标移到顶部栏按钮时，背景不变色的问题
- 修复了一些界面小问题

English:
- Added acrylic thin backdrop
- Fixed an issue where the background did not change color when hovering over the top bar buttons with the mouse
- Fixed some minor UI issues


- 新增高透光壓克力材質
- 修復滑鼠移到頂部欄按鈕時背景不變色的問題
- 修復一些介面上的小問題
- 
# 1.3.9
日期: 2025年07月16日
- 优化词典服务的负载能力，提升输出速度
- 优化mdx的查词速度(大概提升20%-30%)，减少了内存占用
- 优化了暗黑模式下的界面显示
- 修复了关闭窗口后再打开时背景材质不显示的问题
 
Date: July 16, 2025
- Optimized the dictionary service to handle higher loads and improved output speed
- Improved lookup speed in MDX and reduced memory usage
- Enhanced the interface display in dark mode
- Fixed an issue where the backdrop wouldn’t take effect after reopening the window from system tray
  
# 1.3.8
日期: 2025年07月14日
- 优化了mdx的读取性能
- 优化了词典内容的加载和渲染速度
- 修复了在某些情况下mdx文件无法正确加载的问题
- 修改了启动时的一些问题

Date: July 14, 2025
- Optimized the performance of reading MDX files
- Improved the loading and rendering speed of dictionary content
- Fixed an issue where MDX files could not be loaded correctly in certain situations
- Resolved some issues that occurred during startup
  
# 1.3.7

日期: 2025年05月03日
-添加了MCP服务，供AI进行实时词典内容查询

Date: May 3, 2025
- Added MCP service for AI to perform real-time dictionary lookups.

# 1.3.6.0 
日期: 2025年05月03日
- 解决了窗口放大缩小后不能拖动的问题
- 解决了其它一些小问题
- 升级Windows UI组件到1.3.7


- Fixed the issue where the window could not be dragged after resizing
- Fixed some other minor issues
- Upgraded Windows UI components to version 1.7.0


# 1.3.5.0 
日期: 11月10日
- 解决了Edge TTS的连接问题

Date: November 10
- Resolved the connection issue with Edge TTS.
