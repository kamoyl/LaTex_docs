all: dyplom.ps

.tex.dvi:
	latex $<
	bibtex $*
	latex $<
	latex $<

.dvi.ps:
	dvips $* -o

dyplom.ps: dyplom.dvi
	dvips dyplom -o

dyplom.dvi: dyplom.tex r01.tex r02.tex r03.tex r04.tex r05.tex #0podziekowania.tex

clean:

