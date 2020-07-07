presentation.pdf: presentation.tex
	latexmk -xelatex presentation.tex

presentation.tex: presentation.md example.bib
	pandoc -t beamer presentation.md -o presentation.tex --biblatex --standalone

clean:
	latexmk -c
	rm presentation.xdv
	rm presentation.bbl
	rm presentation.nav
	rm presentation.run.xml
	rm presentation.snm
