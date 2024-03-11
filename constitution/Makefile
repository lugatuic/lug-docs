constitution.pdf: constitution.tex

%.pdf: %.tex
	latexmk -pdf -shell-escape -use-make $^

all: hw

clean:
	latexmk -CA
	rm -f *.snm *.nav *.vrb *.pyg
	rm -rf _minted-*/ svg-inkscape/

.PHONY: all clean
