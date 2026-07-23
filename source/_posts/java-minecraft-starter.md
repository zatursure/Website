---
title: 文章模板示例
date: 2026-07-07 18:00:00
updated: 2026-07-07 18:00:00
categories:
  - 博客搭建
tags:
  - Hexo
  - Anzhiyu
  - 写作模板
keywords:
  - Hexo
  - Anzhiyu
  - 博客文章模板
description: 一篇用于验证 Hexo 与 Anzhiyu 主题文章展示效果的标准模板示例。
cover: https://t.alcy.cc/ycy
top_img: https://t.alcy.cc/ycy
comments: true
aside: true
toc: true
copyright: true
katex: true
---

模板
<!-- more -->

## 目标

一篇结构清晰的文章通常先说明问题，再给出步骤，最后补充注意事项：

- 一级标题由文章 `title` 提供，正文从二级标题开始。
- 每个章节只讨论一个主题。
- 代码、命令、配置项使用代码块展示。
- 需要摘要时，把 `<!-- more -->` 放在首段之后。

## Front-matter

```yaml
---
title: 文章标题
date: 2026-07-07 18:00:00
updated: 2026-07-07 18:00:00
categories:
  - 分类名称
tags:
  - 标签一
  - 标签二
keywords:
  - 关键词一
  - 关键词二
description: 概括
cover: /img/default_cover.jpg
top_img: false
comments: true
aside: true
toc: true
copyright: true
---
```

## 正文

### 有序步骤

1. 先描述背景和目标。
2. 再列出实际操作。
3. 最后记录验证方式和后续计划。

### 引用

> 保持文章结构稳定，比一次性写得很复杂更重要。

### 表格

| 字段 | 作用 | 建议 |
| --- | --- | --- |
| `categories` | 文章分类 | 一篇文章放在一个主分类下 |
| `tags` | 文章标签 | 用 2 到 5 个关键词 |
| `description` | 首页和搜索摘要 | 写成一句完整的话 |
| `cover` | 文章封面 | 使用站内图片或可靠外链 |

### 代码块

```bash
hexo new "文章标题"
```

### KaTeX 公式

行内公式适合放在句子中，例如质能方程 $E = mc^2$，或者二次方程的判别式 $\Delta = b^2 - 4ac$。

块级公式适合展示完整推导：

$$
\int_{-\infty}^{\infty} e^{-x^2}\,dx = \sqrt{\pi}
$$

矩阵也可以用 KaTeX 表示：

$$
\begin{bmatrix}
1 & 0 \\
0 & 1
\end{bmatrix}
\begin{bmatrix}
x \\
y
\end{bmatrix}
=
\begin{bmatrix}
x \\
y
\end{bmatrix}
$$

## 链接

[Picture1](https://t.alcy.cc/ycy)