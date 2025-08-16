# v1.5.1.0

## English

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
