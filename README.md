# local-image-batch 📸

[中文](#中文说明) | [English](#english-documentation)

---

## 中文说明

local-image-batch 是一款基于 HTML5 Canvas 和纯前端生态构建的**高保真图片批处理与格式转换工具**。整个处理流程完全在用户本地浏览器沙盒内完成，无需任何后端服务器支持，确保 100% 的数据隐私与极致的性能响应。

🚀 **[点击此处在线体验 Live Demo](https://dagaolaoshi.github.io/WebPicKit/)**

### ✨ 核心特性
- **本地零服务器开销**：利用 HTML5 `FileReader` 与 `Canvas API` 异步解析，不占用任何网络带宽，零隐私泄露风险。
- **高比例批量压缩**：支持将任意常规格式图片批量转换并高效压缩至 `WebP` (推荐)、`JPEG`、`PNG`。
- **实时对比看板**：动态渲染图片队列，直观展示原始体积、转换后体积以及精确的“瘦身”比率。
- **流式客户端打包**：集成 `JSZip` 库，在前端将内存二进制流（Blob）动态组装，实现一键批量导出 `.zip` 归档包。
- **全端响应式设计**：基于 Tailwind CSS 构建，完美适配桌面端拖拽上传与移动端点击操作。

### 🛠️ 技术栈
- **核心引擎**: JavaScript (ES6+) / Canvas API / FileReader API / Blob / URL.createObjectURL- **核心引擎**: JavaScript (ES6 ) / Canvas API / FileReader API / Blob / URL.createObjectURL
- **UI 视图层**: HTML5 / Tailwind CSS / DaisyUI (Modern Dark Theme)- **UI: HTML5 /顺风CSS / DaisyUI（现代黑暗主题）
- **依赖归档**: JSZip.js (v3.10.1 via CDN)

---

## English Documentation   英文文档

local-image-batch is a high-fidelity **client-side image batch processing and format conversion tool** built entirely on the HTML5 Canvas ecosystem. The entire workflow is executed inside the user's local browser sandbox without any backend server overhead, ensuring 100% data privacy and blazing-fast response times.WebPicKit是一个高保真**客户端图像批处理和格式转换工具**完全建立在HTML5画布生态系统。整个工作流在用户的本地浏览器沙盒内执行，没有任何后端服务器开销，确保100%的数据隐私和极快的响应时间。

🚀 **[Live Demo Available Here](https://dagaolaoshi.github.io/WebPicKit/)**

### ✨ Key Features   ###✨主要功能
- **Zero Server Overhead**: Leverages HTML5 `FileReader` and `Canvas API` for asynchronous image parsing, consuming zero network bandwidth with absolute privacy.- **零服务器开销**：利用HTML5 ‘ FileReader ’和‘ Canvas API ’异步图像解析，消耗零网络带宽与绝对隐私。
- **High-Ratio Batch Compression**: Supports batch converting and highly compressing any standard image formats into `WebP` (Recommended), `JPEG`, or `PNG`.- **高比率批量压缩**：支持批量转换和高度压缩任何标准图像格式为‘ WebP ’（推荐），‘ JPEG ’，或‘ PNG ’。
- **Real-time Contrast Dashboard**: Dynamically renders the image processing queue, intuitively visualizing original size, converted size, and precise "slimming" ratios.- **实时对比仪表板**：动态渲染图像处理队列，直观可视化原始大小、转换大小、精确“瘦身”比例。
- **Client-side Stream Bundling**: Integrates the `JSZip` library to dynamically assemble memory binary streams (Blobs) into a `.zip` archive for one-click batch download.- **客户端流捆绑**：集成‘ JSZip ’库来动态组装内存二进制流（blob）到一个‘ .zip ’存档一键批量下载。
- **Fully Responsive UI**: Powered by Tailwind CSS, providing a seamless user experience for both desktop drag-and-drop and mobile click-to-upload.- **完全响应式UI**：由顺风CSS提供支持，为桌面拖放和移动点击上传提供无缝的用户体验。

### 🛠️ Tech Stack   ###推荐️技术堆栈
- **Core Engine**: JavaScript (ES6+) / Canvas API / FileReader API / Blob / URL.createObjectURL-核心引擎**:JavaScript (ES6) / Canvas API / FileReader API / Blob / URL.createObjectURL
- **UI & Styling**: HTML5 / Tailwind CSS / DaisyUI (Modern Dark Theme)- **UI &样式**:HTML5 /顺风CSS / DaisyUI（现代黑暗主题）
- **Third-party Library**: JSZip.js (v3.10.1 via CDN)- **第三方库**:JSZip.js （v3.10.1通过CDN）

### 📄 How to Run Locally###📄如何本地运行
1. Clone this repository:   1. 克隆这个存储库：
```bash   ”“bash
   git clone [https://github.com/dagaolaoshi/WebPicKit.git](https://github.com/dagaolaoshi/WebPicKit.git)
