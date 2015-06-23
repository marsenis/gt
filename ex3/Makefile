LATEX=xelatex

all: ex3.pdf

ex3.pdf: ex3.tex title.tex ../logos/pyrforos.png ../logos/uoa.png
	$(LATEX) ex3.tex
	$(LATEX) ex3.tex

clean:
	$(RM) *.aux *.log

distclean: clean
	$(RM) ex3.pdf
