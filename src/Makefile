TC = xelatex

.PHONY: clean

default: main.pdf

clean:
	rm -f main.{aux,log,nav,out,pdf,snm,toc,vrb}

main.pdf: *.tex sql
	$(TC) -shell-escape main.tex
