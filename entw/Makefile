.PHONY: clean all present view
all: entw_psycho.pdf	

clean:
	rm -f *.log
	rm -f *.aux
	rm -f *.toc
	rm -f *.out
	rm -f *.fdb_latexmk
	rm -f *.fls
	rm -f *.nav
	rm -f *.snm

entw_psycho.pdf: 
	pdflatex entw_psycho.tex

build:
	latexmk -pvc -pdf entw_psycho.tex
