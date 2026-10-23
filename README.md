# Tiny

[中文](#中文) · [English](#english)

Small tools. Native code. Less overhead.

---

## 中文

**Tiny 是一系列小巧、高效的实用程序。**

专注于日常使用中的具体需求，用尽可能小的体积和尽可能少的资源，把功能做好。

### 设计原则

- **原生实现**：优先使用系统自带组件与原生能力，避免引入庞大的框架和第三方依赖。
- **精简高效**：关注程序体积、启动速度和资源占用，减少不必要的功能与后台活动。
- **简单直接**：清晰的界面，直接的操作，让小工具回归工具本身。
- **方便使用**：尽量做到下载即用，无需额外安装运行库或依赖。具体要求以各程序说明为准。

### 程序

| 名称 | 简介 |
| --- | --- |
| **[Tiny PDF Toolkit 1.0](Tiny%20PDF%20Toolkit.exe)** | 约 2.74 MiB 的离线 PDF 工具箱，12 项功能，支持批量处理，适用于 Windows 10 / 11，64 位。 |
| **[Tiny Markdown Reader 1.0](TinyMarkdownReader.exe)** | 约 139 KiB 的原生 Markdown 阅读与编辑工具，适用于 Windows 10 / 11，64 位。 |
| **[Tiny TV PDF Viewer v1.1](TV-PdfViewer-Lite.apk)** | 约 165.5 KiB 的原生 Android TV 大屏阅读与无线推送工具，适用于 Android 5.0+。 |

#### Tiny Markdown Reader 1.0

- 单个 EXE，大小仅 139 KiB，下载即用，无需额外安装运行库。
- 多标签、文档大纲和查找；支持阅读、双栏、源码及基础可视化编辑。
- 常用数学与化学公式的原生排版，支持打印和 PDF 导出。
- 中英文界面，默认跟随系统语言，也可手动切换并记住选择。

#### Tiny TV PDF Viewer v1.1

- 单个 APK 约 165.5 KiB，使用系统 PDF 渲染器与 WebView，无需打包第三方运行库，适用于 Android 5.0+。
- PDF 阅读适配电视遥控器：支持双页画册与单页模式、适宽与适高切换、书签与阅读进度记忆。
- **新增 EPUB 阅读**：支持章节目录、字号调整、遥控器翻页和阅读进度恢复；适用于无 DRM 的普通图文书，需要可用的系统 WebView。
- **新增 WebDAV 网络书库**：浏览局域网 NAS 或其他 WebDAV 服务器中的 PDF / EPUB，下载到缓存后阅读。
- **网页配置 WebDAV**：手机或电脑打开电视显示的局域网地址，点击「配置 WebDAV」，在弹窗中添加、编辑或删除服务器，避免用遥控器输入地址和账号密码。配置页面通过 HTTP 访问，请在可信局域网内使用。
- **自动管理网络缓存**：默认预算 300 MiB，优先清理较久未使用的文件，30 天未访问的缓存会在清理时移除；支持手动清理。正在阅读的文件受到保护，单个超大文件在阅读结束后清理；不影响本地上传图书、NAS 原文件和阅读记录。
- 浏览器支持点击选择或拖拽上传 PDF、EPUB 与 APK，可查看传输进度并在上传后自动打开；APK 会拉起系统安装界面，并在安装结束后清理临时安装包。
- 加强上传完整性检查、路径校验与阅读资源释放；网页底部显示程序名、v1.1 和项目主页。

#### Tiny PDF Toolkit 1.0

- 约 2.74 MiB，单个 EXE，适用于 Windows 10 / 11（64 位）；无需安装额外运行库，文件全程在本地处理。
- 提供解密、合并与书签、提取、拆分、删除、旋转、全文倒序、骑马订拼版、多页合一、页码、文字水印和图片转 PDF，共 12 项工具。解密仅支持空密码或已知密码。
- 添加或拖入文件、文件夹后，通过固定排列的功能标签处理；支持子文件夹、文件多选与顺序调整，启动时默认最大化。
- 旋转、提取等操作支持指定页码、范围及奇偶页；页码可自定义起始页与起始编号，例如前 3 页不编号，就从第 4 页开始。
- 骑马订默认 A4 横向、两页拼满，自动补齐空白页；双面打印选择短边翻转，再沿中缝对折。另支持 2 / 4 合 1。
- 支持中文水印、JPEG / PNG 图片及透明背景。页码和水印以矢量图形添加，不能作为文字复制或搜索。
- 单文件默认在原目录保存为 `原文件名_output.pdf`；批量和拆分默认保存到各原目录的 `output` 文件夹，输出路径及名称均可修改。
- 默认保护原文件，后台任务支持取消，完成后可打开输出位置。PDF 处理使用静态链接的 QPDF、zlib 和 libjpeg，无需外部 PDF 程序；第三方许可已嵌入 EXE。

[下载 Tiny PDF Toolkit 1.0](Tiny%20PDF%20Toolkit.exe?raw=true)

后续程序也将在这里发布。

### 下载与使用

程序直接存放在本仓库中，下载对应文件即可使用：
- **Windows 工具**（`.exe`）：适用于 **Windows 10 / 11，64 位**。
- **Android TV 工具**（`.apk`）：适用于 **Android 5.0 及以上版本**的智能电视、电视盒子与投影仪。

具体要求以各程序说明为准。

### 关于本仓库

本仓库用于分享可运行的程序、使用说明和更新记录，**不包含源代码**。

这些程序都是 vibe coding 的产物，就让成品出来见人，源码留在本地——也算是为未来的 AI 训练数据少添一点噪声。

如遇问题或有改进建议，欢迎通过 **Issues** 反馈。报告问题时，请附上程序版本、系统版本和复现步骤。

[English ↓](#english) · [返回顶部 ↑](#tiny)

---

## English

**Tiny is a collection of small, efficient utilities.**

Each app addresses a practical everyday need, with a focus on useful features, a small footprint, and low resource usage.

### Design Principles

- **Native implementation**: Prefer built-in system components and avoid large frameworks and heavy third-party dependencies.
- **Small and efficient**: Keep executable size, startup time, and resource usage low. Avoid unnecessary features and background activity.
- **Simple to use**: Clear interfaces and straightforward interactions that keep the focus on the task.
- **Easy to run**: Aim for apps that run after downloading, without installing additional runtimes. See each app's documentation for specific requirements.

### Apps

| Name | Description |
| --- | --- |
| **[Tiny PDF Toolkit 1.0](Tiny%20PDF%20Toolkit.exe)** | An offline PDF toolkit, about 2.74 MiB, with 12 tools and batch processing for 64-bit Windows 10 and 11. |
| **[Tiny Markdown Reader 1.0](TinyMarkdownReader.exe)** | A native Markdown reader and editor, about 139 KiB, for 64-bit Windows 10 and 11. |
| **[Tiny TV PDF Viewer v1.1](TV-PdfViewer-Lite.apk)** | An Android TV PDF / EPUB reader and wireless upload tool, about 165.5 KiB, for Android 5.0+. |

#### Tiny Markdown Reader 1.0

- A single EXE of just 139 KiB, ready to run without installing additional runtimes.
- Tabs, document outline, and search; reading, split, source, and basic visual editing modes.
- Native layout for common math and chemical formulas, plus printing and PDF export.
- Chinese and English UI, following the system language by default, with a saved manual override.

#### Tiny TV PDF Viewer v1.1

- A single APK of about 165.5 KiB for Android 5.0+, using the system PDF renderer and WebView without bundled third-party runtime libraries.
- Remote-friendly PDF reading: dual-page booklet and single-page modes, fit-width/fit-height, bookmarks, and saved reading progress.
- **New EPUB reader**: chapter navigation, adjustable font size, remote-control paging, and resume support. Intended for ordinary DRM-free books; requires a working system WebView.
- **New WebDAV library**: browse PDF / EPUB books on a LAN NAS or other WebDAV server and download them into a managed cache for reading.
- **Configure WebDAV from a browser**: open the TV's LAN address on a phone or PC, then use the WebDAV configuration dialog to add, edit, or remove servers without entering addresses and credentials with the TV remote. The page uses HTTP; use it on a trusted LAN.
- **Managed network cache**: a default 300 MiB budget, least-recently-used cleanup, and removal of entries not accessed for 30 days when cleanup runs, plus manual clearing. Active books are protected; oversized files are removed after reading. Local uploads, NAS originals, and reading records are preserved.
- Click to select or drag and drop PDF, EPUB, and APK files in the browser, with transfer progress and optional auto-open. APK uploads launch the system installer and clean up the temporary package after installation ends.
- Improved upload integrity checks, path validation, and reader resource cleanup. The browser footer shows the app name, v1.1, and project homepage.

#### Tiny PDF Toolkit 1.0

- A single EXE of about 2.74 MiB for 64-bit Windows 10 and 11. No additional runtime installation; files are processed locally.
- Twelve tools: decrypt, merge with bookmarks, extract, split, delete, rotate, reverse, booklet imposition, N-up layout, page numbering, text watermarks, and images to PDF. Decryption requires an empty or known password.
- Add or drop files and folders, then choose a tool from fixed-position tabs. Supports subfolders, multiple selection, and file reordering; opens maximized by default.
- Select page ranges and odd/even pages for applicable tools. Set the numbering start page and starting number; for example, start on page 4 to leave the first three pages unnumbered.
- Booklet layout defaults to landscape A4 with two pages per sheet side and automatic blank-page padding. Print double-sided with short-edge binding, then fold along the center. Also supports 2-up and 4-up layouts.
- Supports Chinese watermarks, JPEG/PNG images, and transparency. Added numbers and watermarks are vector outlines, not searchable or selectable text.
- A single-file result defaults to `original_name_output.pdf` beside the source. Batch and split results default to an `output` subfolder beside each source; output paths and names are editable.
- Protects source files, supports background cancellation, and can open the output location. QPDF, zlib, and libjpeg are statically linked; no external PDF application is required. Third-party notices are embedded in the EXE.

[Download Tiny PDF Toolkit 1.0](Tiny%20PDF%20Toolkit.exe?raw=true)

Future apps will be published here as well.

### Download and Use

Apps are stored directly in this repository. Download the corresponding file to get started:
- **Windows utilities** (`.exe`): For **64-bit Windows 10 and 11**.
- **Android TV utilities** (`.apk`): For smart TVs, TV boxes, and projectors running **Android 5.0+**.

See each app's documentation for specific requirements.

### About This Repository

This repository shares ready-to-run apps, documentation, and update history. **Source code is not included.**

These apps are all products of vibe coding, so the finished apps are shared while the source stays local—consider it a small effort to keep a little noise out of future AI training data.

Bug reports and suggestions are welcome through **Issues**. For bug reports, please include the app version, OS version, and steps to reproduce the problem.

[中文 ↑](#中文) · [Back to top ↑](#tiny)
