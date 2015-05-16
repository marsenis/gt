LATEX=xelatex

all: ex2.pdf

ex2.pdf: ex2.tex title.tex pyrforos.png uoa.png
	$(LATEX) ex2.tex
	$(LATEX) ex2.tex

clean:
	$(RM) *.aux *.log

distclean:
	$(RM) ex2.pdf
