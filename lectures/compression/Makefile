
TALK = talk

open: $(TALK).pdf
	open $(TALK).pdf

$(TALK).pdf: $(TALK).tex
	pdflatex $(TALK).tex
	pdflatex $(TALK).tex

clean:
	rm *.toc *.log *.out $(TALK).pdf *.aux *.nav *.vrb *.snm *~
