---
title: Fuwari 的简易指南
published: 2024-04-01
description: "如何使用该博客模板"
image: "./cover.jpeg"
tags: ["Fuwari", "Blogging", "自定义"]
category: Fuwari 使用说明
draft: false
---

> 图片来源: [点击查看](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/208fc754-890d-4adb-9753-2c963332675d/width=2048/01651-1456859105-(colour_1.5),girl,_Blue,yellow,green,cyan,purple,red,pink,_best,8k,UHD,masterpiece,male%20focus,%201boy,gloves,%20ponytail,%20long%20hair,.jpeg)

该博客使用 [Astro](https://astro.build/) 搭建. 对于本指南中未提及的内容，您可在 [Astro Docs](https://docs.astro.build/) 寻找答案.

## 博客前言

```yaml
---
title: 我的第一篇博客
published: 2023-09-09
description: 这是我的第一篇使用 Astro 的博客.
image: ./cover.jpg
tags: [Foo, Bar]
category: 前端
draft: false
---
```

| 代码     | 说明                                                                                                                                                                                                 |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `title`       | 博客的标题                                                                                                                                                                                      |
| `published`   | 博客的发布日期                                                                                                                                                                      |
| `description` | 博客内容的简单描述，用于主页显示                                                                                                                                                   |
| `image`       | 帖子封面的图片路径  <br/>1. 以 `http://` 或 `https://`开头: 使用网络图片<br/>2. 以 `/`开头: 图片读取于 `public` 文件夹<br/>3. 无开头: 读取于 markdown 所在的文件夹 |
| `tags`        | 博客标签                                                                                                                                                                                       |
| `category`    | 博客分类                                                                                                                                                                  |
| `draft`        | 是否列为草稿，列为草稿则不显示                                                                                                                                                 |

## 帖子的文件位置



您的帖子存放在 `src/content/posts/` directory. 您也可以创立如下文件夹更好的管理帖子

```
src/content/posts/
├── post-1.md
└── post-2/
    ├── cover.png
    └── index.md
```

>该帖翻译自:[https://fuwari.vercel.app/](https://fuwari.vercel.app/)

