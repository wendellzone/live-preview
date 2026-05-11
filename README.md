# Live Preview

一个单文件 SPA，在浏览器里实时预览 Markdown / JSON / JSON Diff / PlantUML。

## 视图

- **综合（Markdown）** — 多文章工作台，支持代码块内嵌 PlantUML 与 JSON 渲染，导出 MD / HTML / PDF
- **JSON** — 可展开树视图，工具栏：格式化 / 压缩 / 全展开 / 全折叠 / 复制；错误三层兜底
- **JSON Diff** — 行级高亮直接在两个文本框里显示，新增/删除/修改三色标记
- **PlantUML** — 实时渲染 SVG，支持缩放、复制分享链接、导出 SVG/PNG

## 用法

直接打开 `index.html`。所有内容存在浏览器 localStorage，不上传任何数据。

## 在线访问

GitHub Pages: https://jiashuwang0.github.io/live-preview/

## 依赖（CDN）

marked@4.3.0 / dompurify@3.1.6 / highlight.js@11.9.0 / pako@2.1.0 / html2canvas@1.4.1 / jspdf@2.5.1
