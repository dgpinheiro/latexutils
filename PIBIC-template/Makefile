all: 
	rm -f ./section/*.aux *.aux *.log *.blg *.bbl *.dvi *.toc *.lot *.lof *.sigla* *.idx *.symbol*
	pdflatex main
	bibtex main1
	pdflatex main
	pdflatex main

clean:
	rm -f ./section/*.aux *.aux *.log *.blg *.bbl *.dvi *.ps *.pdf *.toc *.lot *.lof
