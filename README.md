# 极光PDF · Aurora PDF

> 让 PDF 里凝固的文字，如极光般灵动呈现。

![Release](https://img.shields.io/github/v/release/haoeastspeed/AuroraPDF?color=2A7A9C)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11%20x64-2A7A9C)
![Downloads](https://img.shields.io/github/downloads/haoeastspeed/AuroraPDF/total?color=3FA7C9)

轻量、极速、本地优先的 PDF 编辑器。原生编译、启动快、占用低，正文文字可就地直接修改。

- **产品主页**：https://haoeastspeed.github.io/AuroraPDF/
- **下载最新版**：[Releases 页面](https://github.com/haoeastspeed/AuroraPDF/releases/latest)

---

## 功能

- **极速渲染查看**：PDFium 高清渲染，Native AOT 原生编译，启动快、高 DPI 清晰，内存 / CPU 占用低。
- **正文文字就地编辑**：点击命中原有文字块，按原字体大小直接修改；支持中文（CJK 字体嵌入）与新增文字，不弹小框、不生成叠加小字。
- **页面编辑**：新增空白页、复制、删除、旋转、移动排序、提取指定页面，缩略图右键即可操作。
- **多视图浏览**：单页、连续滚动、双页对开与网格布局；滚轮与键盘翻页，缩略图支持键盘导航。
- **格式关联**：一键将极光PDF 加入系统 PDF“打开方式”并注册文档类型（不显示 .exe 扩展名）。
- **明暗双主题**：界面简洁、色调统一。

## 自动更新

软件内置托管自动更新，更新清单为 [`update.json`](update.json)：

- 在「设置与关于」中一键检查更新。
- 后台下载最新安装包并做 **SHA256 完整性校验**，随后启动安装程序原地覆盖升级（保留配置与文件关联）。

清单地址（软件内使用，含多源回退）：

```
https://raw.githubusercontent.com/haoeastspeed/AuroraPDF/main/update.json
https://cdn.jsdelivr.net/gh/haoeastspeed/AuroraPDF@main/update.json
```

## 系统要求

- Windows 10 / 11（64 位）
- 安装后即可离线使用

## 隐私

本地优先，**文件不上传、不联网处理文档内容**；仅在「检查更新」时访问本公开仓库以获取版本清单与安装包。

## 关于源码

本仓库为**成品发布与自动更新托管**（公开）。应用源代码保留在**私有仓库**，不随本仓库公开。

## 技术栈与第三方许可

C# / .NET 10 + Avalonia UI；渲染与编辑：PDFium（通过 PDFiumCore，Apache-2.0 / BSD）；Native AOT 发布。各组件版权归各自所有者，详见安装目录 `LICENSES` 与随包许可声明。

© 2026 haoeastspeed
