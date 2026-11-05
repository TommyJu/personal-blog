# My workflow for adding blog posts

## 1. Create a new page bundle
```
content/
└── posts/
    └── learning-hugo/
        ├── index.md
        ├── cover.png
        └── image-to-include-in-article.png 
```

## 2. Edit post metadata
Open `index.md`
```
---
title: "Learning Hugo"
date: 2026-11-04
draft: false
tags: ["Hugo", "Web Development"]
cover:
  image: "cover.png"
  alt: "Hugo logo"
  caption: "Learning to build static websites with Hugo"
  relative: true
---

Write post content here... 
```

## 3. Push changes to version control
