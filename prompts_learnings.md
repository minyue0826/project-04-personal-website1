# Agent 协同学习 Prompt 记录与心得

本文档用于记录在 AI Agent 辅助下理解与搭建 MkDocs 网站的过程。

## 1. 概念理解 Prompt
* **提问**：“请帮我用简单的话解释一下 MkDocs 的工作原理，以及它和传统的动态网站有什么区别？”
* **Agent 总结**：MkDocs 将 Markdown 源文件直接编译转换为静态 HTML/CSS/JS 文件，无需后端数据库，渲染速度极快且极易部署。

## 2. CSS 样式微调 Prompt
* **提问**：“我想把 MkDocs Material 主题的主容器改成半透明白色背景、带有卡片阴影和柔和渐变网页背景，请帮我写出 CSS。”
* **代码生成**：生成了 `extra.css` 中的 `linear-gradient` 与 `box-shadow` 样式。
