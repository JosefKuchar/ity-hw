pdf:
	latex proj3.tex
	latex proj3.tex
	dvips proj3.dvi
	ps2pdf -sPAPERSIZE=a4 proj3.ps

overlay: pdf
	pdftk proj3.pdf multibackground vzor.pdf output overlay.pdf

clean:
	rm -f *.aux *.dvi *.out *.log *.ps proj3.pdf
