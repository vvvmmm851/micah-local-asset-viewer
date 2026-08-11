# 本地资产看图器

本地资产看图器是一款 Windows 本地素材浏览工具，用于快速查看图片、HDR/EXR、设计文件、PDF、视频静态画面和常见 3D 文件的缩略图或静态预览。

## 下载

请在本仓库的 **Releases** 页面下载最新的：

`micah-local-asset-viewer-vX.Y.Z-Windows-x64.zip`

不要下载 GitHub 自动生成的 `Source code` 压缩包，它不是可运行软件。

## 使用

1. 下载 Windows x64 ZIP。
2. 将整个 ZIP 解压到普通文件夹，不要只拖出 EXE。
3. 双击 `本地资产看图器.exe`。
4. 如果提示缺少 WebView2，运行 `WebView2\MicrosoftEdgeWebView2RuntimeInstallerX64.exe`，安装后重新打开软件。

进入软件后可选择素材文件夹，也可以把 Windows 文件资源管理器中的文件拖到右侧预览区。软件会切换到文件所在目录并预览该文件。视频只显示静态画面，不播放。

软件不需要安装 Node.js、Rust、Cargo 或 Visual Studio。

## 更新与卸载

- 更新：下载更高版本 ZIP，解压到新文件夹后运行。
- 卸载：关闭软件，删除整个解压文件夹。
- `_runtime` 是运行组件目录，请勿删除或移动其中的文件。

## 隐私

软件本地运行，不上传、移动、删除或改写用户素材。故障日志只写入软件目录下的 `logs` 文件夹。

完整变更见 [CHANGELOG.md](CHANGELOG.md)，隐私说明见 [PRIVACY.md](PRIVACY.md)。
