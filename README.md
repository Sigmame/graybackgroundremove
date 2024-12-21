# 在线图片去灰底工具 | Online Gray Background Removal Tool

一个简单高效的在线工具，用于去除图片中的灰色背景。特别适用于扫描文档、证件照片等。
A simple and efficient online tool for removing gray backgrounds from images, especially useful for scanned documents and ID photos.

[在线演示 | Live Demo](https://sigmame.github.io/graybackgroundremove/)

## ✨ 主要特性 | Key Features

- 🚀 无需下载软件，完全在线处理 | No software download required, fully online processing
- 💡 智能灰度阈值调节 | Smart grayscale threshold adjustment
- 📄 支持多种图片格式 | Multiple image formats supported
- 🔄 批量处理能力 | Batch processing capability
- 🌍 中英文双语界面 | Bilingual interface (Chinese/English)
- 💾 一键下载处理结果 | One-click download of processed results

## 🛠️ 技术栈 | Tech Stack

- 纯前端实现 | Pure frontend implementation
- HTML5 Canvas
- 原生 JavaScript | Vanilla JavaScript
- 响应式设计 | Responsive Design

## 📝 使用说明 | Usage Guide

1. 选择图片 | Select Image
   - 点击"选择图片"按钮上传需要处理的图片
   - Click "Select Image" button to upload the image you want to process

2. 调整阈值 | Adjust Threshold
   - 使用滑块或直接输入数值调整灰度阈值
   - Use slider or directly input value to adjust grayscale threshold
   - 推荐阈值范围 | Recommended threshold ranges:
     - 普通文档 | Regular documents: 180-220
     - 证件照片 | ID photos: 200-230

3. 处理图片 | Process Image
   - 点击"处理图片"按钮
   - Click "Process Image" button

4. 下载结果 | Download Result
   - 点击"下载处理后的图片"保存结果
   - Click "Download Processed Image" to save the result

## 📋 支持格式 | Supported Formats

- JPG/JPEG
- PNG
- BMP
- 其他常见图片格式 | Other common image formats

## ⚠️ 使用建议 | Usage Tips

- 建议图片尺寸不超过 4000×4000 像素
- Recommended image size: not exceeding 4000×4000 pixels
- 处理大文件前建议先进行压缩
- Compression recommended before processing large files
- 对比度较低的图片可能需要多次调整阈值
- Images with low contrast may require multiple threshold adjustments

## 🔍 常见问题 | FAQ

### 如何选择合适的阈值？ | How to choose the right threshold?
阈值决定了哪些灰色区域会被转换为白色。阈值越高，越多的灰色区域会被处理。建议从200开始调整，直到达到最佳效果。

The threshold determines which gray areas will be converted to white. Higher threshold means more gray areas will be processed. Start from 200 and adjust as needed.

### 为什么处理后的图片有些地方发白？ | Why do some areas become too white after processing?
这可能是因为阈值设置过低，建议适当调高阈值，或者对原图进行适当的对比度调整后再处理。

This might be due to a low threshold setting. Try increasing the threshold or adjusting the contrast of the original image before processing.

## 📦 本地部署 | Local Deployment

1. 克隆仓库 | Clone repository
```bash
git clone https://github.com/Sigmame/graybackgroundremove.git

2. 直接在浏览器中打开 index.html 文件
   Simply open index.html in your browser

## 🤝 贡献 | Contributing

欢迎提交 Issue 和 Pull Request
Issues and Pull Requests are welcome


## 🔗 相关链接 | Related Links

- [项目主页 | Project Homepage](https://github.com/Sigmame/graybackgroundremove)
- [问题反馈 | Bug Report](https://github.com/Sigmame/graybackgroundremove/issues)
- [功能建议 | Feature Request](https://github.com/Sigmame/graybackgroundremove/issues)
