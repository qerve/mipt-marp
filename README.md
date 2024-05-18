# mipt-marp
Simple marp presentation for MIPT routine

Useful for quick presentations that can be generated using AI with prompted Markdown syntax for marp

# Installation
1. Download [mipt.css](https://github.com/qerve/mipt-marp/blob/0ba50e01039ef3be55fe9be34920e0dcfad01b50/mipt.css "download") and move it to your project directory
2. Add start config to your `.md` file that shown below
```
---
marp: true
theme: mipt
_class: lead
paginate: true
math: katex
header: 'Header text ![header](https://raw.githubusercontent.com/qerve/mipt-marp/main/header_white.png)'
title: titlename
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---
```
3. Run your markdown file by `marp --allow-local-files filename.md --theme mipt.css`. Use `--pdf` if needed

If any problems occur, see the example

![[1jpg]('example/1jpg.png')](https://raw.githubusercontent.com/qerve/mipt-marp/main/example/1jpg.png)
![[2jpg]('example/2jpg.png')](https://raw.githubusercontent.com/qerve/mipt-marp/main/example/2jpg.png)
