# ooxml-viewer

一个在线工具，用于预览 Office Open XML 文件（包括 docx、xlsx、pptx）内部的 XML 文件。

## 在线体验

无需本地安装，直接访问：[https://xna00.github.io/ooxml-viewer/](https://xna00.github.io/ooxml-viewer/) 即可在线预览和使用。

## 功能

- 支持上传 Office Open XML 文件（docx、xlsx、pptx）。
- 自动解压并展示文件中的所有 XML 文件列表。
- 点击文件名可查看对应 XML 内容，支持高亮显示。

## 本地开发

1. 安装依赖（如有）：
    ```sh
    npm install
    ```
2. 启动本地静态服务器（推荐使用 http-server）：
    ```sh
    npx http-server ./src
    ```
3. 在浏览器中打开页面：
    ```sh
    http://localhost:8080
    ```


## License

MIT