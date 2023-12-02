---
date: 2023-12-01
authors: [dumitrux]
description: >
  MkDocs Material Blog
categories:
  - mkdocs
---

# MkDocs Material <!-- omit in toc -->

- [Built-in blog plugin](https://squidfunk.github.io/mkdocs-material/plugins/blog/)
- [Setting up a blog](https://squidfunk.github.io/mkdocs-material/setup/setting-up-a-blog/)
- [Adding a comment system](https://squidfunk.github.io/mkdocs-material/setup/adding-a-comment-system/)
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/blog/)

## Setup

```bash
python -m venv venv
source venv/bin/activate

pip install mkdocs-material
pip install mkdocs-minify-plugin
pip install mkdocs-glightbox

mkdocs serve
```

Use again:
  
```bash
source venv/bin/activate
mkdocs serve
```

## Blog

```bash
``` { .sh .no-copy }
.
├─ docs/
│  └─ blog/
│     ├─ posts/
│     └─ index.md
└─ mkdocs.yml
```
