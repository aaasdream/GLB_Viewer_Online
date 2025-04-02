# AAASDREAM GLB Viewer

## Overview
AAASDREAM is a modern, web-based 3D model viewer for GLB files. It provides a clean, minimalist interface for viewing 3D models directly in your browser without requiring any additional software or plugins.

## Online Version
You can access the online version of AAASDREAM GLB Viewer at:
### [https://aaasdream.github.io/GLB_Viewer_Online/](https://aaasdream.github.io/GLB_Viewer_Online/)

No installation required - just visit the website and start viewing your GLB models immediately.

## Features
- Load GLB files from URLs or local storage
- Interactive 3D model viewing with camera controls
- Responsive design that works on desktop and mobile devices
- Dark theme UI for comfortable viewing experience
- Automatic model scaling and positioning
- Cross-platform compatibility

## Installation
If you prefer a local installation, simply clone the repository and open the `index.html` file in a web browser:

```bash
git clone https://github.com/yourusername/aaasdream.git
cd aaasdream
```

Then open `index.html` in your preferred browser.

## Usage
1. Open the application in your browser
2. Click the upload button in the top-left corner
3. Either:
   - Enter a URL to a GLB file and click "Load from URL"
   - Or click "Select GLB file" to choose a file from your device
4. Use mouse/touch controls to interact with the model:
   - Left mouse button: Rotate the model
   - Right mouse button: Pan the view
   - Mouse wheel: Zoom in/out

You can also load a model directly by appending a URL parameter: `index.html?url=https://example.com/model.glb`

## Requirements
- Modern web browser with WebGL support (Chrome, Firefox, Safari, Edge)
- Internet connection for loading external models or CDN resources

## Technologies Used
- Three.js for 3D rendering
- ES6 Modules
- Modern CSS with CSS Variables

---

# AAASDREAM GLB 檢視器

## 概述
AAASDREAM 是一個現代化的網頁版 3D 模型檢視器，專為 GLB 檔案設計。它提供了簡潔、極簡的介面，讓您直接在瀏覽器中查看 3D 模型，無需安裝任何額外的軟體或外掛程式。

## 在線版本
您可以直接通過以下網址訪問 AAASDREAM GLB 檢視器的在線版本：
### [https://aaasdream.github.io/GLB_Viewer_Online/](https://aaasdream.github.io/GLB_Viewer_Online/)

無需安裝 - 只需訪問網站即可立即開始查看您的 GLB 模型。

## 特點
- 從 URL 或本地儲存載入 GLB 檔案
- 互動式 3D 模型檢視，具有相機控制功能
- 回應式設計，適用於桌面和移動裝置
- 暗色主題界面，提供舒適的觀看體驗
- 自動模型縮放和定位
- 跨平台兼容性

## 安裝
如果您偏好本地安裝，只需克隆存儲庫並在網頁瀏覽器中打開 `index.html` 檔案：

```bash
git clone https://github.com/yourusername/aaasdream.git
cd aaasdream
```

然後在您喜好的瀏覽器中打開 `index.html`。

## 使用方法
1. 在瀏覽器中開啟應用程式
2. 點擊左上角的上傳按鈕
3. 選擇以下其中一種方式：
   - 輸入 GLB 檔案的 URL 並點擊「Load from URL」
   - 或點擊「Select GLB file」從您的裝置中選擇檔案
4. 使用滑鼠/觸控控制來互動模型：
   - 左鍵：旋轉模型
   - 右鍵：平移視圖
   - 滑鼠滾輪：縮放

您也可以通過附加 URL 參數直接載入模型：`index.html?url=https://example.com/model.glb`

## 系統需求
- 支援 WebGL 的現代網頁瀏覽器（Chrome、Firefox、Safari、Edge）
- 網路連接（用於載入外部模型或 CDN 資源）

## 使用技術
- Three.js 進行 3D 渲染
- ES6 模組
- 使用 CSS 變數的現代 CSS 