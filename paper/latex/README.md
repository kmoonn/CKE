# 硕士论文

题目：基于可控知识编辑的大语言模型生成内容安全方法研究。

- `main-2025-newform.tex`：论文入口。
- `tex/`：论文信息、中英文摘要、五章正文、致谢、科研成果与附录。
- `ref.bib`：参考文献。
- `figures/`：论文使用的图片。
- `whut-thesis.cls`、`.sty`、`.bst`：学校版式和引用依赖。

使用 XeLaTeX 与 BibTeX。在项目根目录执行 `latexmk` 或 `make`，也可手动编译：

```text
xelatex main-2025-newform
bibtex main-2025-newform
xelatex main-2025-newform
xelatex main-2025-newform
```

沿用 Windows 字体配置。未验证的实验、结论及系统测试在正文中标为待完成。

参考文献依赖来自 [gbt7714-bibtex-style v2.1.8](https://github.com/zepinglee/gbt7714-bibtex-style/releases/tag/v2.1.8)，遵循 LPPL 1.3c 或更新版本；版权及许可声明保留在源文件头部。
