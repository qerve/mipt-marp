# mipt-marp
Simple marp presentation for MIPT routine

Useful for quick presentations that can be generated using AI with prompted Markdown syntax for marp

# Installation
1. Donwload mipt.css and move it to your project directory
2. Run your markdown file by `marp --allow-local-files filename.md --theme mipt.css`
3. Use `--pdf` if needed

![[1jpg]('example/1jpg.png')](https://raw.githubusercontent.com/qerve/mipt-marp/main/example/1jpg.png)
![[2jpg]('example/2jpg.png')](https://raw.githubusercontent.com/qerve/mipt-marp/main/example/2jpg.png)

# Config
```---
marp: true
theme: mipt
_class: lead
paginate: true
math: katex
header: 'Header text ![header](https://raw.githubusercontent.com/qerve/mipt-marp/main/header_white.png)'
title: titlename
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---```
