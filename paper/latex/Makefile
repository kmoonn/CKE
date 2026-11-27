# 当前硕士论文编译入口
MAIN = main-2025-newform
LATEX = xelatex -interaction=nonstopmode -file-line-error
BIBTEX = bibtex

.PHONY: all lm

all:
	$(LATEX) $(MAIN)
	$(BIBTEX) $(MAIN)
	$(LATEX) $(MAIN)
	$(LATEX) $(MAIN)

lm:
	latexmk -xelatex $(MAIN).tex
