LATEX=xelatex

all: ex1.pdf

ex1.pdf: ex1.tex title.tex pyrforos.png uoa.png
	$(LATEX) ex1.tex
	$(LATEX) ex1.tex

clean:
	$(RM) *.aux *.log

distclean: clean
	$(RM) ex1.pdf
