
# GitHub文件夹下载器

## 简介

GitHub文件夹下载器是一个完全在浏览器中运行的工具，允许用户从GitHub下载文件夹。它不存储任何用户数据，提供了快速、免费的下载服务，并且与浏览器扩展无缝集成。

## 功能

- 从GitHub仓库下载指定文件夹。
- 支持多种镜像源（如GitHub官方、ghproxy、ddlc等）。
- 自定义镜像功能，用户可以添加自己的镜像源。
- 显示下载进度条和成功/失败的文件统计。
- 下载完成后，用户可以下载ZIP文件。

## 使用说明

1. **输入GitHub文件夹URL**：在输入框中粘贴GitHub文件夹的URL。
2. **选择镜像源**：从下拉菜单中选择一个镜像源，或者添加自定义镜像。
3. **下载文件夹**：点击“下载文件夹”按钮，开始下载过程。
4. **下载完成**：下载完成后，点击“下载ZIP文件”按钮，获取压缩包。

## 依赖

- [JSZip](https://cdnjs.cloudflare.com/ajax/libs/jszip/3.10.1/jszip.min.js)
- [FileSaver.js](https://cdnjs.cloudflare.com/ajax/libs/FileSaver.js/2.0.5/FileSaver.min.js)

## 示例

```plaintext
https://github.com/pyenv-win/pyenv-win/tree/master/docs
```

## 错误处理

- 如果下载失败，尝试更换镜像源。
- 如果API请求达到限制，请尝试更换镜像源。

