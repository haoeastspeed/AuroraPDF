# 极光PDF · Aurora PDF

> 让 PDF 里凝固的文字，如极光般灵动呈现。

![Release](https://img.shields.io/github/v/release/haoeastspeed/AuroraPDF?color=2A7A9C)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11%20x64-2A7A9C)
![Downloads](https://img.shields.io/github/downloads/haoeastspeed/AuroraPDF/total?color=3FA7C9)

本地优先、隐私安全、支持**文本智能重排**的 PDF 编辑器。

- **产品主页**：https://haoeastspeed.github.io/AuroraPDF/
- **下载最新版**：[Releases 页面](https://github.com/haoeastspeed/AuroraPDF/releases/latest)

---

## 功能

- **结构化正文编辑**：重建版面语义，真正移除原文字并按段落宽度智能重排；内容增多自动块推移、跨页续排，改字不再错位。
- **页面管理**：增删空白页、复制、旋转、拖拽排序、上移 / 下移、合并外部 PDF、提取页面，支持撤销重做。
- **注释批注**：高亮 / 下划线 / 删除线 / 便利贴 / 矩形 / 椭圆 / 箭头 / 自由文本 / 铅笔手绘。
- **OCR 文字识别**：扫描件、图片页自动识别，叠加可选文本层，变为可搜索 / 可复制。
- **密文永久遮蔽（Redaction）**：文字内容流与图像像素真删，清理元数据等隐藏信息，删除不可恢复。
- **PKI 数字签名**：自签 / 导入证书、可见与不可见签名、多人会签、完整性校验。
- **文档增强**：水印、背景、页眉页脚、插入图片、区域擦除。
- **双内核 / 双主题**：默认 PDFium（Apache-2.0，许可干净），可切换 MuPDF；明暗双主题、Ribbon 功能区。

## 自动更新

软件内置托管自动更新，更新清单为 [`update.json`](update.json)：

- 启动后按频率在后台静默检查，也可在功能区手动「检查更新」。
- 后台下载最新安装包并做 **SHA256 完整性校验**，随后启动安装程序原地覆盖升级（保留配置与文件关联）。

清单地址（软件内使用）：

```
https://raw.githubusercontent.com/haoeastspeed/AuroraPDF/main/update.json
```

## 系统要求

- Windows 10 / 11（64 位）
- 安装后即可离线使用

## 隐私

本地优先，**文件不上传、不联网处理文档内容**；仅在「检查更新」时访问本公开仓库以获取版本清单与安装包。

## 关于源码

本仓库为**成品发布与自动更新托管**（公开）。应用源代码保留在**私有仓库**，不随本仓库公开。

## 第三方组件与许可

GUI：PySide6 / Qt（LGPL）；PDF 内核：pypdfium2 / PDFium（Apache-2.0），可选 PyMuPDF / MuPDF（AGPL-3.0 / 商业双许可）；结构处理：pypdf（BSD-3-Clause）；OCR：RapidOCR / ONNX Runtime；数字签名：pyhanko（MIT）。各组件版权归各自所有者，详见安装目录与随包许可声明。

© 2026 haoeastspeed
