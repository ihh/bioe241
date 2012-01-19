
all: $(subst .tex,.pdf.open,$(wildcard *.tex))

%.pdf: %.tex
	pdflatex -shell-escape $< >$@

%.open: %
	open $*

.SECONDARY:
