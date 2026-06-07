# local-image-batch 📸

---

## 中文说明

local-image-batch 是一款基于 HTML5 Canvas 和纯前端生态构建的**高保真图片批处理与格式转换工具**。整个处理流程完全在用户本地浏览器沙盒内完成，无需任何后端服务器支持，确保 100% 的数据隐私与极致的性能响应。

🚀 **[点击此处在线体验](https://dagaolaoshi.github.io/local-image-batch/)**

### ✨ 核心特性
- **本地零服务器开销**：利用 HTML5 `FileReader` 与 `Canvas API` 异步解析，不占用任何网络带宽，零隐私泄露风险。
- **高比例批量压缩**：支持将任意常规格式图片批量转换并高效压缩至 `WebP` (推荐)、`JPEG`、`PNG`。
- **实时对比看板**：动态渲染图片队列，直观展示原始体积、转换后体积以及精确的“瘦身”比率。
- **流式客户端打包**：集成 `JSZip` 库，在前端将内存二进制流（Blob）动态组装，实现一键批量导出 `.zip` 归档包。
- **全端响应式设计**：基于 Tailwind CSS 构建，完美适配桌面端拖拽上传与移动端点击操作。

### 🛠️ 技术栈
- **核心引擎**: JavaScript (ES6+) / Canvas API / FileReader API / Blob / URL.createObjectURL
- **UI 视图层**: HTML5 / Tailwind CSS / DaisyUI (Modern Dark Theme)
- **依赖归档**: JSZip.js (v3.10.1 via CDN)


---

## English Documentation

WebPicKit is a high-fidelity **client-side image batch processing and format conversion tool** built entirely on the HTML5 Canvas ecosystem. The entire workflow is executed inside the user's local browser sandbox without any backend server overhead, ensuring 100% data privacy and blazing-fast response times.

🚀 **[Live Demo Available Here](https://dagaolaoshi.github.io/local-image-batch/)**

### ✨ Key Features
- **Zero Server Overhead**: Leverages HTML5 `FileReader` and `Canvas API` for asynchronous image parsing, consuming zero network bandwidth with absolute privacy.
- **High-Ratio Batch Compression**: Supports batch converting and highly compressing any standard image formats into `WebP` (Recommended), `JPEG`, or `PNG`.
- **Real-time Contrast Dashboard**: Dynamically renders the image processing queue, intuitively visualizing original size, converted size, and precise "slimming" ratios.
- **Client-side Stream Bundling**: Integrates the `JSZip` library to dynamically assemble memory binary streams (Blobs) into a `.zip` archive for one-click batch download.
- **Fully Responsive UI**: Powered by Tailwind CSS, providing a seamless user experience for both desktop drag-and-drop and mobile click-to-upload.

### 🛠️ Tech Stack
- **Core Engine**: JavaScript (ES6+) / Canvas API / FileReader API / Blob / URL.createObjectURL
- **UI & Styling**: HTML5 / Tailwind CSS / DaisyUI (Modern Dark Theme)
- **Third-party Library**: JSZip.js (v3.10.1 via CDN)

### 📄 How to Run Locally
1. Clone this repository:
```bash
   git clone [https://github.com/dagaolaoshi/local-image-batch.git](https://github.com/dagaolaoshi/local-image-batch.git)
